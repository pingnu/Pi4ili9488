Used GoogleAI "python code for ili9488"

LCD_DC   = 8
LCD_CS   = 9
LCD_SCK  = 10
LCD_MOSI = 11
LCD_MISO = 12
LCD_BL   = 13
LCD_RST  = 15
TP_CS    = 16
TP_IRQ   = 17

Raspberry Pi4

LCD_DC = 24
LCD_CS = 8
LCD_SCK = 11
LCD_MOSI = 10
LCD_MISO = 09
LCD_BL = 13
LCD_RST = 25
TP_CS = 16
TP_IRQ = 17



Traceback (most recent call last):
  File "/home/carl/Pi4ili9488/ledbutton2.py", line 9, in <module>
    import ili9488
  File "/home/carl/Pi4ili9488/ili9488.py", line 20, in <module>
    import ustruct  # type: ignore
ModuleNotFoundError: No module named 'ustruct'

        Traceback (most recent call last):

  File "/home/carl/Pi4ili9488/picotest.py", line 5, in <module>
    from ili9488 import Display, color565, bswap16
  File "/home/carl/Pi4ili9488/ili9488.py", line 20, in <module>
    import ustruct  # type: ignore
ModuleNotFoundError: No module named 'ustruct'

> > > 
