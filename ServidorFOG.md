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

En aquest cas, el proces de captura es exactament de la mateixa forma que com ho hem fet en windows:

despres de habilitar el boot per lan a la maquina ubuntu la enjeguem i arranquem desde lan i seleccionem la registracio del host:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/157d0a00-990d-4c1b-9521-83edb94399e3)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/2f161137-7ed5-41b7-848f-858f21256a0f)

un cop capturat el host, creem la imatge al servidor fog

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/274f5136-68b9-4ede-8e31-edce45685fe8)

tornarem a iniciar la maquina ubuntu desde lan i la imatge comensara a ser capturada

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/229bdbc2-1cc1-4efd-9012-c8e52b68bbff)

finalment ja tenim les dues, la imatge de windows y tambe la de ubuntu: 

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/df076f18-6691-4e34-bbc2-9b949f20adb8)


---

## Instal·lacio Amb Imatge Windows ##

preparem una maquina amb un disc buit, i amb el boot per xarxa habilitat

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/a4f0a42f-0ee0-4c00-bcd3-e844f5cce4b3)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/1e2a1960-877b-4358-a6f8-1ab79a31b7ed)

i ara seleccionem la opcio, deploy image:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/127c2ac9-81b1-4fd9-a1d4-85d16bb99105)

i seleccionem la imatge que volem instalar al disc:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/5c87d52f-f9d2-4ed2-9bf3-250b47c3b65f)

la instalacio comensara sense cap problema
  
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/4029ba36-43f9-4918-85cd-f677b2cc1753)
  
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/c0d3c5e5-a093-4426-9a04-966904baf721)
  
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/346b4c95-7d67-440e-9703-b961801de779)

un cop finalitze la instalacio ja tenim el windows en el disc:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/ccfd02fb-78dd-414a-9724-78c4136ed14e)

aquest windows habia sigut capturat amb un google chrome


---

## Instal·lacio Amb Imatge Ubuntu ##

El proces amb ubuntu es exactament el mateix, primer que tot necesitem una maquina amb un disc buit i amb el boot per xarxa habilitat:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/e30535c5-c6bd-4f21-997f-16dd660f033f)

fem boot desde lan

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/054cdb08-5a92-4140-aa37-6cc056281741)


i seguidament seleccionem la opcio de deploy image, aquesta vegada seleccionarem la de ubuntu i farem la instalacio amb ubuntu:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/1d04c2c5-e8db-4e1d-a2bd-23018f02d935)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/64105b3e-0d4b-420a-a4e8-6e333abac0e0)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/5f8639ce-23f9-4db0-8445-5cfb0f3a450f)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/41e6eed2-0086-4d78-be34-15dcdad8bf0f)

un cop a finalitzat ja tenim el ubuntu instalat desde el servidor fog:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/80c73ea3-ec80-4ec5-b601-ba3a0a11d39e)

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/62e245ac-4cff-4c11-8c74-bec9e31d0c48)

## Llençar Paquet Que S'instal·li Als Clients ## 

Descarreguem el firefox

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/61996abc-4168-452a-8eb3-af363ceab273)

i el seleccionem de snaping file 
![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/18dc820e-9bfe-4999-922f-e1f1da7504bc)

entrem al host que volem llançar la instalacio:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/26a5522c-e604-428a-b5d6-3b0643f05b68)

entrem a snapins

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/eaa1847e-33d4-4e74-b70a-63b18f30ddf7)

seleccionem el de firefox: 

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/ccc6379b-1051-4b15-951c-5b318f5c42e2)

l'afetgim:

![image](https://github.com/EricOrtegaGi/MP01-ServidorFOG/assets/114953110/3d85a694-df51-4b74-b434-a2376c6c38f6)










