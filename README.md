# STM32_NanoEdge_AI_Studio_DataLogger_Ver1
NanoEdge AI Studio는 ST사에서 ML 모델을 보다 쉽게 On Device하기 위한 프로그램입니다.
NanoEdge AI Studio 프로그램에서 DataLogger를 지원하는 보드는 한정적입니다. 
저는 STM사의 Nucleo-F411RE 보드를 사용해서 #define DataLogger 및 Run(ML Model을 동작 시키는..) 코드를 설계해서 해보자는 계획을 가지고 있습니다.(추가적으로 STM32H747I-DISCO 보드도..)

# F411re Logger
ADC1, UART2, TIMER1을 사용하여 설계하였습니다.


