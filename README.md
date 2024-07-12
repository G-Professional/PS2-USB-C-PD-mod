# PS2-USB-C-PD-mod

This is a USB-C power mod for the PS2 SCPH 50001

![sample](images/preview1.png)

To Do:
  - Desolder 4 pin connector from PSU
  - ~~Design USB C trigger board mount that fits into power connector and switch slot.~~
  - ~~3d print trigger board mount~~
  - ~~verify fit and adjust 3d design as needed~~

Final design finished. Fitment is good

First thing to do is to short the correct pins on the board to enable 12V. These will be the 2 middle pins

Next I will test to ensure 12V before connecting to system

Next solder connector to the trigger board.

Finally, test that the system turns on.

Parts:
  - Trigger board -
    - https://www.amazon.com/dp/B08LDJBN8P?ref=ppx_yo2ov_dt_b_product_details&th=1

Links:
 - USB C PD info
   - perhaps in the future I would like to design my own trigger board
   - https://resources.altium.com/p/add-usb-type-c-power-delivery-your-designs
   - https://octopart.com/search?q=cypd3177-24lqxq&currency=USD&specs=0
   - https://www.infineon.com/dgdl/Infineon-EZ-PD_BCR_Datasheet_USB_Type-C_Port_Controller_for_Power_Sinks-DataSheet-v03_00-EN.pdf?fileId=8ac78c8c7d0d8da4017d0ee7ce9d70ad
