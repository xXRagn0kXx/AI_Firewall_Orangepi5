
1 Download img file 

https://www.armbian.com/orangepi-5-max/

2 Step Guide

https://www.xda-developers.com/how-i-used-the-npu-on-my-orange-pi-5-pro-to-run-llms/


ranking: 

1	PHI-3 Mini 3.8B	Lo subo al número 1. El RK3588 es excelente para la eficiencia. PHI-3 Mini es conocido por su increíble rendimiento en tareas de benchmark de razonamiento y lógica, acercándose a modelos 7B. Su tamaño compacto (≈ 3.8B) y su eficiencia lo hacen ideal para la NPU. Si tu Orange Pi se usa para lógica, razonamiento o código, este es el campeón.
2	Qwen3-4B	Lo subo al número 2. Ya vimos en nuestra conversación anterior que existen optimizaciones directas con RKLLM para este modelo, incluyendo modos de pensamiento dual. Esto le da una ventaja de rendimiento real y eficiencia multilingüe sobre otros en este hardware.
3	Mistral-4B	Lo bajo al número 3. Sigue siendo el "caballo de batalla" por excelencia: gran calidad, muy buen soporte y excelente en el ecosistema GGUF (que probablemente usarás si no usas RKLLM). Es la apuesta más segura y fiable.
4	Gemma-3-4B	Lo bajo al número 4. Aunque tiene la máxima calidad pura en 4B (como indica la lista original), a menudo es el más "exigente" o menos estable al inicio en hardware no-Google, requiriendo a veces cuantizaciones más específicas (como QAT) para brillar de verdad en la NPU.
5	Llama-3.1/Minitron 4B	Se mantiene. Excelente compatibilidad y gran comunidad, pero sus rivales lo superan en calidad-eficiencia para tareas específicas en este rango de tamaño.

Exportar a Hojas de cálculo
