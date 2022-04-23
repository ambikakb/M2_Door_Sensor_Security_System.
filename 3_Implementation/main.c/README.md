\**
@file main.c
 * @author Ambika K B (you@domain.com)
 * @brief 
 * @version 0.1
 * @date 2022-03-08
 * 
 * @copyright Copyright (c) 2022
 * 
 */
 #include <avr/io.h>
int main(void)
{
 DDRB=DDRB&0b11111101;//fd
 DDRC=DDRC|0b01000000;//40
 while(1)
 {
if(PINB & 0b00000010)//02
 PORTC=PORTC|0b01000000;//40
  else
  PORTC=PORTC&0b10111111;//bf
 }
 return 0;
