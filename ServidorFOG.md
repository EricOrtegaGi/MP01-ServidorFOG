# Instal·lacio Del Servidor FOG # 

Clonem el repositori al nostre servidor:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/b5d7d163-1788-4293-aa87-1040305ae56d)

l'extraem i executem el script de instal·lacio

Aqui procedim amb la instal·lacio i la configuracio inicial:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/f9443256-932f-4e0a-a18d-fcf8e6467cbc)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/ee44d438-2046-4bf1-a91c-d9b9e0e534ab)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/aa090494-9f56-4315-9bd8-d8424a808f16)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/9bebf6b6-87c2-4bc7-ba6c-4f0d70375f5f)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/1e1eb3a6-8b96-43bd-8409-fae34b7101c1)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/2968c7c3-f044-48fd-abe5-1bf531e435a8)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/a3d77e9b-15c1-4912-a12c-c6cc361a6434)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/c1251783-40ab-4f84-92ac-5ea4642e2148)


---

## Captura Desde Client Windows ##


Per fer la captura dels clients, el primer que tindrem que fer es habilitar el boot desde lan: 

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/b78cfa9d-4d93-4f33-abdb-21655cc989b5)

Quan arranquem iniciem per lan i seleccionem la seguent opcio:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/5be4d070-635b-4721-b5fe-6ab2900b2d35)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/5ff43ec4-e2c1-44c2-ae00-711267c0a2b2)
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/f58764b7-5196-48cc-b4c8-37fefbb3536b)

un cop hem deixat que el servidor capturi el host veurem com la activitat en el servidor canvia, i si anem a hosts veurem el seguent:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/72d9c94e-a4c3-4836-980a-eb5d063b7243)

ara apagarem el client, crearem una nova imatge al servidor amb host bios i efi tipus SANBOOT: 

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/6b05754d-c2c0-412d-b9a3-6239f9e05b42)

ara entrarem al host que hem capturat, anirem a basic tasks i farem la captura de la imatge

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/58727930-66a5-404e-97b8-200df204e970)

i seleccionarem la imatge que acabem de crear com a host:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/fcd143ad-d79a-4660-9c1c-33ee9bf0cf5c)

ara tindrem que tornar a enjegar el client windows i tornar fer boot desde lan i la copia de la imatge comensara: 

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/64566a59-af14-4c46-9c46-5e7298eb9a86)

un cop ha acabat al servidor si anem a imatges vorem com tenim la imatge de windows, i ja no pesa 0 si no que ara pesa 10gb pel que significa que s'ha capturat crrectament:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/3b360975-7aec-4422-8408-48aadcb35122)





---

## Captura Desde Client Ubuntu ##

---

## Instal·lacio Amb Imatge Windows ##

---

## Instal·lacio Amb Imatge Ubuntu ##
