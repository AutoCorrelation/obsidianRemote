
| State | Name            | Explain                                          |
| :---- | --------------- | ------------------------------------------------ |
| 설계    | 기기 구조<br>       | 보드 및 센서, 안테나 구조 설계<br>(잡아당겼을 때 뽑히면 안됨)           |
|       | 사용 모듈<br>(통신방법) | IMU(I2C)<br>BMP(I2C)<br>SDcard(SPI)<br>Lora(SPI) |
|       | 센서              ch roll (XYZ)<br>고도                       |
|       | 원격 통신<br>(및 백업) | Euler An Eule Euler Euler Angle, V Euler An Euler Angle, Velocit Euler Angle Euler Angle,  Euler Angl Euler Angle, Velocity,  Euler Ang Euler Angle, Velocity, Euler Angle, Euler Angle, Velocity, Accelerate, Time<br>을 최대한 오류 없이 통신      |                                                  |
| 발사 전  | 원격 통신           | Remote로 Avionics를 제어.                         Euler Angle(백)<br>V Euler Angle(백업)<br>V Euler Angle(백업ㅇ)<br>Velocity, Accelerate, Time<br>을 최대한 오류 없이 통신.    |              Euler Angle(백업?)<br>Velo Euler Angle(백업?)<br>Veloc Euler Angle(백업?)<br>Veloci Euler Angle(백업?)<br>Velocity, Accelerate, Time(위치측위)<br>을 최대한 오류 없이 통신. 스템을 이용해<br>실시간 정보 확인                        |
|       |                 |                                                  |
|  Euler Angle(백 Euler Angle(백업)<br>Velocity, A Euler Angle(백업)<br>Velocity, Accelerate, Time(위치측위?)< Euler Angle(백업)<br> Euler Angle(백업)<br>Velocity, Accelerate, T Euler Angle(백업)<br>Velocity, Accelerate, Time(위치측위?)<br>등을 오류 없이 빠    |

