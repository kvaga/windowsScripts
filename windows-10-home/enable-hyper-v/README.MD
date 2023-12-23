## Checking a Requirements
Check your windows 10 HOME installation has all necessary settings enabled
```
> cmd.exe
> systeminfo
...
Требования Hyper-V:               Расширения режима мониторинга виртуальной машины: Да
                                  Виртуализация включена во встроенном ПО: Да
                                  Преобразование адресов второго уровня: Да
                                  Доступно предотвращение выполнения данных: Да
```
## Installation plugins
Run as administration the script: enable-hyper-v/enable-hyper-v.bat
```
> enable-hyper-v.bat
```
On a final step press 'Y' for restart a system
## Checking Hyper V was installed
On windows search line tap a command 
```
hyper v
````
and open a programm
