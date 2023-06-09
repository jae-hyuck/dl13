## GAN (Generative Adversarial Network: 생성적 적대 신경망)
- ## DCGAN (Deep Convolutional GAN)
- - ## mnist
- - ## cifar10
## GAN 이란
- GAN은 생성자(generator)와 판별자(discriminator)라는 두 개의 신경망으로 이루어져 있습니다. 생성자는 무작위 노이즈 벡터를 입력으로 받아 실제 데이터와 유사한 가짜 데이터를 생성하고, 판별자는 생성자가 생성한 가짜 데이터와 실제 데이터를 구분하여 진위 여부를 판별합니다. 이 과정에서 생성자는 판별자를 속이기 위해 더 실제와 유사한 데이터를 생성하게 되고, 판별자는 생성자가 생성한 데이터와 실제 데이터를 잘 구분할 수 있도록 학습하게 됩니다.

- 예를 들어, 생성자는 어떤 특정 이미지를 만들어 내기 위해 이미지의 구조와 특징을 파악하고 그에 맞는 가짜 이미지를 생성합니다. 판별자는 생성자가 생성한 가짜 이미지와 실제 이미지를 비교하여 얼마나 유사한지를 판별합니다. 이러한 과정을 반복하여 생성자가 더욱 실제와 유사한 이미지를 만들어내고, 판별자가 더욱 정확하게 판별할 수 있도록 학습하게 됩니다.

- GAN은 이미지, 음성, 텍스트 등 다양한 데이터 유형에서 사용될 수 있으며, 그 유연성과 성능 때문에 딥러닝 연구 분야에서 광범위하게 사용되고 있습니다. 특히, GAN을 사용하여 이미지를 생성하는 연구나, 스타일 변환, 이미지 보강, 이미지 합성 등 다양한 응용 분야에서 유용하게 활용되고 있습니다.
