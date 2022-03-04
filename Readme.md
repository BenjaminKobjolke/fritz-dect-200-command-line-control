# Turn [Fritz!DECT 200](https://avm.de/produkte/fritzdect/fritzdect-200/) devices on/off from the windows command line 

## Original code
https://github.com/bpicode/fritzctl

## install 
- copy .fritzctl.json to your user folder (e.g. C:\Users\USERNAME)
- add fritzbox url and logindata to .fritzctl.json in your userfolder

## use
- use list.bat to list the available fritz dect 200 devices
- copy the name of the result like "FRITZ!DECT WHATEVER"
- add the name to off.bat and on.bat

    Example

    ```
    fritzctl.exe switch on "FRITZ!DECT WHATEVER"
    ```

- execute off.bat/on.bat to turn your fritz dect 200 off or on :)


