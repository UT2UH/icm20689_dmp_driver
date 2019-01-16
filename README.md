# ICM20689 DMP Driver

invensense��˾��һ��������ICM20689����û���������ٷ��ṩһ��ICM20789�汾��G55���ϵ�demo��
���Ƿǳ��������ã��һ�������汾ɾ�����޸ĳ���һ����STM32�Ϸ���ʹ�õ��������롣

## ƽ̨����

Chip �� STM32F405RGT6
IDE :  Keil
ST lib �� HAL

## �ļ�����

��ֲ�ļ� ��STM32�ϵ������������ļ�����ֲ���Լ��Ĺ���ֻ��Ҫ�������3���ļ���  
icm20689��ֲ�汾demo ��һ����ֲdemo�����Բ������demo����spi�����Լ�����ṹ��  

�����Ұ�dmp������ش��붼��װ����lib���棬�����Ҫԭʼ�汾�뷢�ʼ���ϵ�ҡ�

## ʹ��ע��

������Ҫʹ���߹�ע��ֻ�����¼�������
|���� |  ����  |  ע��  |
|----|----|----|
| void icm20689_dmp_setup() |  ��ʼ��DMP�����������ǣ�  |  �����ڲ�����HAL_Delay�������Ҫ����SPI��ϵͳʱ��֮��  |
| void get_dmp_data() |  ��ȡDMP���������̬�ǣ�0��ʾ�ɹ���1��ʾʧ��  |   ���������DMP������̬��Ƶ��Ϊ200Hz����˶�ȡ����ʱ����ʧ�ܵ��������  |
| unsigned char MPU_Get_Accelerometer(short *ax,short *ay,short *az) |  ��ȡ���ٶ���Ϣ |  ע�ⵥλ��ʹ��DMPģʽ��ʼ�������̱ض���+/- 4g  |
| unsigned char MPU_Get_Gyroscope(short *gx,short *gy,short *gz)  |  ��ȡ���ٶ�  |  ע�ⵥλ��ʹ��DMPģʽ��ʼ�������̱ض���+/- 2000dps  |

## Author Information
Name :  LD
E-mail :  adayimaxiga@hotmail.com
Wechat :  adayimaxiga
2019.1.16