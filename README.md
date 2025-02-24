# PS2-USB-C-PD-mod

This is a USB-C power mod for the PS2 SCPH 50001

![sample](images/preview1.png)

Parts:
  - Trigger board -
    - https://www.amazon.com/dp/B08LDJBN8P?ref=ppx_yo2ov_dt_b_product_details&th=1
   
Instructions:

*WARNING: This was designed for my specific needs. I did not check to see if this will work for every fat model PS2. I would not be surprised if other models/PSU use different voltages. Sending more voltage than a device needs will damage it!

First step is to short these 2 small middle pins on the trigger module. This will enable 12V. Check with a multimeter to ensure 12V +-.1V. If it is too low, the PS2 will not stay powered on. Too high and it will probably damage the PS2.

<img src="https://github.com/chucacabrawow/PS2-USB-C-PD-mod/blob/main/images/Trigger_Mod.jpg" width=30% height=30%>

Next is to wire it to the connector.

<img src="https://github.com/chucacabrawow/PS2-USB-C-PD-mod/blob/main/images/Pinout.jpg" width=40% height=40%>

Next slot the module into the adapter, connect to the mobo. Double check orientation here, the connector is ambiguous.

<img src="https://github.com/chucacabrawow/PS2-USB-C-PD-mod/blob/main/images/Connected.jpg" width=40% height=40%>

The finished product.

<img src="https://github.com/chucacabrawow/PS2-USB-C-PD-mod/blob/main/images/Installed.jpg" width=40% height=40%>


Notes: 
  - output of stock PSU was 12.03V, triggerboard was 12.10V
  - personally, I dislike how incredibly tiny the trigger board is.
  - I wonder if there's a way to incorporate a power switch like stock.
  - With the final design, the fitment is very tight. I'm not actually sure if the trigger module can be removed with out damaging it.

Links:

https://cults3d.com/en/3d-model/tool/ps2-usb-c-pd-mount

 - USB C PD info
   - perhaps in the future I would like to design my own trigger board
   - https://resources.altium.com/p/add-usb-type-c-power-delivery-your-designs
   - https://octopart.com/search?q=cypd3177-24lqxq&currency=USD&specs=0
   - https://www.infineon.com/dgdl/Infineon-EZ-PD_BCR_Datasheet_USB_Type-C_Port_Controller_for_Power_Sinks-DataSheet-v03_00-EN.pdf?fileId=8ac78c8c7d0d8da4017d0ee7ce9d70ad
