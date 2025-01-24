# STM32_NanoEdge_AI_Studio_DataLogger_Ver1
NanoEdge AI Studio는 ST사에서 ML 모델을 보다 쉽게 On Device하기 위한 프로그램입니다.
NanoEdge AI Studio 프로그램에서 DataLogger를 지원하는 보드는 한정적입니다. 
저는 STM사의 Nucleo-F411RE 보드를 사용해서 #define DataLogger 및 Run(ML Model을 동작 시키는..) 코드를 설계해서 해보자는 계획을 가지고 있습니다.
최종적으로 우리는 직렬 아크 고장(DC ARC FAULT)를 ML Model을 만들어 On Device하여 검증해보겠습니다. Ver2를 기대해주세요!

# F411re Logger
ADC1, UART2, TIMER1을 사용하여 설계하였습니다.

# ADC

![image](https://github.com/user-attachments/assets/7c1e2982-5714-48de-a59c-dc7723e3af4a)

# TIMER

![image](https://github.com/user-attachments/assets/3b9cc7cd-5d90-4308-834d-3374baea16a5)

# UART

![image](https://github.com/user-attachments/assets/b6c6d5ee-5e2a-4f8e-bbf6-0f77de677b9b)

# CLK

![image](https://github.com/user-attachments/assets/3566493f-c16b-4a64-9708-082eedd0641a)

# Test in NanoEdge AI Studio

![image](https://github.com/user-attachments/assets/a5c06a51-8b57-4aa9-aa98-a991ccb4bc01)

코드는 main.c를 확인하세요. 어렵지 않습니다. Study.zip은 프로젝트 압축 파일입니다.
100Khz 1024 샘플을 ADC 합니다.
Ver2에서는 NanoEdge AI Studio에서 만든 ML 모델을 IDE에서 로드하고 모델을 동작시키는 Run코드를 만들어서 DC ARC FAULT 검증을 해보는 시간을 가지겠습니다.  


