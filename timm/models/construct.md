#### 模型文件
beit.py - 实现了BEiT模型，一个基于BERT的图像变换器，使用自监督学习方法。

cait.py - 实现了CaiT模型，这是一种图像变换器，专注于类别注意力机制。

coat.py - 包含CoaT模型，一种结合了卷积和注意力机制的变换器。

convit.py - 实现了ConViT模型，引入了带有软归纳偏置的视觉变换器。

convnext.py - ConvNeXt模型的实现，是根据Transformers的设计改进的CNN。

densenet.py - 包含DenseNet模型，一个通过增强特征重用的深度卷积网络。

efficientnet.py - 包含EfficientNet模型系列，通过复合缩放方法进行优化的网络。

mlp_mixer.py - 实现了MLP-Mixer架构，这是一种全连接层构成的视觉模型。

mobilenetv3.py - MobileNetV3模型的实现，为移动设备优化的轻量级网络。

resnet.py - 包含ResNet及其变体，是深度卷积网络中非常基础的架构。

vision_transformer.py - 实现了Vision Transformer (ViT)，直接将自然语言处理中的变换器应用于图像。

#### 实用工具和辅助文件
factory.py - 提供创建模型的工厂方法，支持从配置创建模型的功能。

features.py - 包含特征提取相关的功能，用于在模型中提取中间层的输出。

helpers.py - 包含多种辅助函数，如加载预训练权重、调整模型架构等。

hub.py - 配置与PyTorch Hub集成，允许直接从Hub加载预训练模型。

registry.py - 包含注册表实现，用于管理不同的模型和组件。

_builder.py - 包含构建网络的底层逻辑，如创建卷积层、注意力层等。

_pretrained.py - 管理预训练模型的加载逻辑，确保可以从官方源载入权重。

#### 专用组件文件
_efficientnet_blocks.py - EfficientNet模型中使用的网络块实现。

_efficientnet_builder.py - 构建EfficientNet模型的工具。

#### 高级特性与创新模型
swin_transformer.py - Swin Transformer模型，使用滑动窗口注意力机制。

volo.py - VOLO模型的实现，一种高效的视觉Outlooker变换器。

xcit.py - XCiT模型，一种跨协方差图像变换器。