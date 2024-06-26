昇腾开源
============

.. -----------------------------------------
.. Page TOC
.. -----------------------------------------
.. toctree::
   :maxdepth: 2
   :hidden:
   :includehidden:
   :caption: 开始使用

   sources/ascend/quick_install.rst

.. toctree::
   :maxdepth: 2
   :hidden:
   :includehidden:
   :caption: 原生支持的AI项目

   sources/pytorch/index.rst
   sources/llamafactory/index.rst

.. warning::

   文档仍在开发中，内容可能存在错误，内容可能会随时更新，请勿将其用于生产环境。

选择您的偏好，并按照 :doc:`快速安装昇腾环境<sources/ascend/quick_install>` 的安装指导进行操作。

安装成功后，请参考各项目的快速开始和样例来开始使用昇腾AI处理器。

.. raw:: html

   <div class="container bg-white flex flex-col items-center">
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/llama-factory.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">LLaMA-Factory</h2>
                        <p class="text-gray-600 desc">便捷高效的大模型微调工具。V0.7.1版本起支持昇腾。</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="https://github.com/hiyouga/LLaMA-Factory">官方链接</a>
                    <span class="split">|</span>
                    <a href="sources/llamafactory/install.html">安装指南</a>
                    <span class="split">|</span>
                    <a href="sources/llamafactory/quick_start.html">快速上手</a>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/pytorch.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">PyTorch</h2>
                        <p class="text-gray-600 desc">PyTorch AI框架  2.1版本官方支持昇腾</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="https://pytorch.org">官方链接</a>
                    <span class="split">|</span>
                    <a href="sources/pytorch/install.html">安装指南</a>
                    <span class="split">|</span>
                    <a href="sources/pytorch/quick_start.html">快速上手</a>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/onnxruntime.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">ONNX Runtime</h2>
                        <p class="text-gray-600 desc">跨平台、高性能 ML 推理和训练加速器。v1.13.1版本起原生支持昇腾</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 4 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/deepspeed.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">DeepSpeed</h2>
                        <p class="text-gray-600 desc">深度学习优化库，使得分布式训练和推理变得简单、高效、有效。
                            V0.10.1版本起支持昇腾。</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 5 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/opencv.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">OpenCV</h2>
                        <p class="text-gray-600 desc">开源计算机视觉库</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 6 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/sd-webui.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">Stable Diffusion web UI</h2>
                        <p class="text-gray-600 desc">Stable diffusion可视化工具链</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 7 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/huggingface.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">Transformers</h2>
                        <p class="text-gray-600 desc">适用于 Pytorch、TensorFlow 和 JAX 先进的机器学习库
                            v4.32.0起支持昇腾</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 8 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/diffusers.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">Diffusers</h2>
                        <p class="text-gray-600 desc">图像和音频生成等扩散模型工具链</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
            <!-- Card 9 -->
            <div class="box rounded-lg p-4 flex flex-col items-center">
                <div class="flex items-center mb-4">
                    <div class="img w-16 h-16 rounded-md mr-4" style="background-image: url('_static/images/huggingface.png')"></div>
                    <div>
                        <h2 class="text-lg font-semibold">Accelerate</h2>
                        <p class="text-gray-600 desc">图像和音频生成等扩散模型工具链</p>
                    </div>
                </div>
                <div class="flex-grow"></div>
                <div class="flex space-x-4 text-blue-600">
                    <a href="#">官方链接</a>
                    <span class="split">|</span>
                    <a href="#">安装指南</a>
                    <span class="split">|</span>
                    <a href="#">快速上手</a>
                </div>
            </div>
        </div>
    </div>
