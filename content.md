![гипотезы AI](https://github.com/Romanru5116/Charge/blob/6bc1dc13b96c6c143da9833eaec9f7e182db8f9e/PIC/Screenshot%20xiaomi_power%20from%202026-06-19%2010-30-23.png)
г
проверка батареи
How to Check Battery Status
Using ACPI Tool: If you prefer a simpler, classic summary, you can install and run acpitool (available in most distribution repositories like sudo apt install acpitool). 
To see detailed information, use:bashacpitool -B

 ![acpitool-B](https://github.com/Romanru5116/Charge/blob/0682888fa0ab3efc7a623af0ad7234c1324605ee/PIC/Screenshot%20BatteryLook%20from%202026-06-19%2010-38-44.png)
c ACPI вроде как все хорошо
![acpi](https://github.com/Romanru5116/Charge/blob/c259a4ac7f38696075bff726b0bd6c634ced2732/Screenshot%20PowerBatfrom%202026-06-19%2010-56-15.png)

 общее устрояство
 ![описание](https://github.com/Romanru5116/Charge/blob/5232c3f17db6d985eff7b3ac856c595062227195/PIC/Screenshot%20powerUSBnot%20from%202026-06-19%2011-24-51.png)

компоненты: 
несколько плат(2?)
собственно контроллер заряда
BQ24192 (или BQ24192M), а также BQ25710 (или BQ25700A), которые часто работают в паре с основным контроллером USB Type-C (например, TPS65988).
