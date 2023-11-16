-- Creación de la estructura establecida

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/4e19c1c8-b563-40d2-8f0d-c1f21e3fc6ab)

-- Creación de las bases del proyecto

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/c9ad9f0f-a2af-4bda-8db1-24f0e5ade0b7)

-- kustomize de bases 

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/e41f5524-7224-4d6c-8c19-e4a112017c41)

-- Creación de los componentes del proyecto

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/eac16f14-2763-4322-b6b1-ca3ecd6cea1e)

-- Creación del dockerfile para el backend

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/bb9bfacf-aee3-480c-8357-827f63395d12)

-- Creación del overlay para el entorno de dev

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/995967e7-dc86-454d-a825-f6de00e2fe9e)

-- Kustomize del entorno de dev 

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/51309b99-6013-43f7-8d9e-24e0623202dc)

-- Creación del overlay para pro

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/c7ecfd67-9148-4f1b-8dda-9825c2d89e8b)

-- Kustomize de pro

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/bfff9876-825e-4347-923d-5a5ad6aaca43)


-- Creación del overlay para test

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/f5014e58-f8ee-498a-9d21-4d9ad1221630)

-- Kustomize para el entorno de test

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/ca0c2369-7d3d-4edb-a6d0-35e07993b349)

-- Values para el chart de test

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/eac57180-c051-4437-b482-6f693172bb17)

* Para iniciar el entrono de dev *

-- Accedemos al overlay y creamos el manifiesto con kustomize

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/fc6bbb9b-cbf0-4a8f-834a-63a7d92f17de)

-- Ejecutamos y vreificamos

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/a2dd4755-8d20-4899-a8dd-0db067632bac)

-- Accedemos al servicio de proxy expuesto

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/38c8caf0-379c-4bd0-982c-b1b5c8dd750c)

* Para iniciar el entrono de pro *

-- Hacemos el mismo proceso para cerar el manifiesto y ejecutamos 

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/292886ac-fb4b-4126-a163-b26ef41320a5)

-- Verificamos que si funcione

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/f10f75b2-92b4-421f-92a3-b11a13cedc44)

* Para iniciar el entrono de test *

-- Generamos el manifiesto habilitando el helm e iniciamos

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/01ba91f5-0bb2-4b72-90c1-26c981ef4d84)

-- Verificamos que estén corriendo

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/106688c6-455b-40e3-8761-d5d130e4d96d)

-- Verificamos

![image](https://github.com/EduarXavier/examen4-k8s/assets/84883446/47ef4924-55af-4513-89b3-cb7b112e5323)

(Los manifiestos se encuentran en los archivos subidos)
