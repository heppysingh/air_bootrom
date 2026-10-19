# air_bootrom

This contains the required files to pass Download Agent Authentication and allows you to unbrick your devices if you had engineering preloader flashed :/
Works on Devices with codename `air`:-  
- Redmi 13C 5G  
- Redmi 13R 5G  
- POCO M6 5G   
Usage instructions :-  
Install mtkclient on your computer   
```
python3 mtk.py printgpt --stock --loader ~/DA_BR.bin --preloader ~/preloader_air.bin --auth ~/auth_sv5.auth
```

