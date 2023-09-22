# BLE Serial Terminal Example
[LiveDemo](https://katonobu.github.io/ble-serial-terminal/)

# change history by katonobu
## 2023/09/07
- `serial-terminal\.github\workflows\build_and_deploy.yml`
    - delete 
- `serial-terminal\README.md`    
    - add this section 
- `src\index.ts`,`index.html`
    - Delete polyfill functions.
## 2023/09/08
- `src\index.ts`
    - Chagen to use JsSerialWeb
- `vite.config.ts`
    - Don't check ESLint(to PASS lib), this may revert in future.
