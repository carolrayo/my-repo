
## Este repositorio ha sido creado para el ejemplo 2.

## Este archivo ha sido editado para el ejemplo 3.

## Para esta tarea he elegido el repositorio de mi compañero de clase Adrián Martín.

## Ejemplo 1:

#### Clonamos su repositorio a nuestra máquina: 
`git clone https://github.com/AdrianMartinN/Tarea_3_New_Branch.git`

![clonar](https://user-images.githubusercontent.com/91874629/153830335-746b717f-57c0-4c02-9212-cf816ce57916.png)

#### Nos cambiamos de directorio poniendo el nombre:
`cd Tarea_3_New_Branch`

![cd repo](https://user-images.githubusercontent.com/91874629/153830661-b5f311e5-0347-4294-8451-56597150edb7.png)

#### Creamos una nueva rama:
`git branch my-branch`

![nueva rama](https://user-images.githubusercontent.com/91874629/153830817-01c8148b-701e-49d1-b8b0-3a9e88cc2701.png)

#### Nos cambiamos a esa nueva rama:
`git checkout my-branch`

![cambiar a la nueva rama](https://user-images.githubusercontent.com/91874629/153830968-545d70de-1660-4051-b174-fe3353674562.png)

#### Voy a editar el archivo readme.md del repositorio clonado de Adrián Martín.

#### Habiéndolo editado pongo el archivo en el área stage:
`git add README.MD`

![añadido](https://user-images.githubusercontent.com/91874629/153832119-03eca183-919f-4316-a307-2156d9547ad6.png)

#### Miro el status para saber los cambios:
`git status `

![status](https://user-images.githubusercontent.com/91874629/153832364-1f3a2776-af0a-41ec-8e40-e413aeb35e62.png)

#### Hacemos commit y añadimos un comentario:
`git commit -m "comentario"`

![commit](https://user-images.githubusercontent.com/91874629/153832546-8356be58-1df0-4a0c-8015-8ab49d91eecc.png)

#### Hacemos push de los cambios:
`git push --set-upstream origin my-branch`

![push](https://user-images.githubusercontent.com/91874629/153834321-c3836c71-5327-45fc-a3b8-9c5ecfb34d42.png)


#### Creamos un pull request y fusionamos:
![pull](https://user-images.githubusercontent.com/91874629/153835308-05072d25-f0fb-4fe4-a356-e82a63a6dc37.png)


## Ejemplo 2:

#### Creamos un nuevo repositorio:
`git init my-repo`

![nuevo repo](https://user-images.githubusercontent.com/91874629/153836879-476e1157-01fa-4ff7-bd42-6d46ec06fa3c.png)

#### Nos movemos a la dirección:
`cd my-repo`

![moverse dentro](https://user-images.githubusercontent.com/91874629/153837038-6c800624-9267-489c-aa26-539597a76f3b.png)


#### Creamos un nuevo archivo:
`touch README.md`

![crear nuevo archivo](https://user-images.githubusercontent.com/91874629/153837398-fe49a1c6-a0e9-45ef-9a71-afa0efacc0d5.png)


#### Añadimos al stage:
`git add README.md`

![stage](https://user-images.githubusercontent.com/91874629/153837894-d5690db6-9d77-4707-8c7d-bcae38476cab.png)

#### Hacemos commit:
`git commit -m "Commit inicial de README"`

![commit](https://user-images.githubusercontent.com/91874629/153838204-ff97e3c3-527e-420e-9574-0e4541c00a92.png)


#### Creamos un repositorio con el mismo nombre en github. Terminamos con un push
`git push origin master`

![push](https://user-images.githubusercontent.com/91874629/153840539-06fbba7d-d08c-44b7-9289-a1a5ede81a57.png)


## Ejemplo 3:

#### Una vez en nuestro repositorio queremos entrar en nuestra nueva rama creada en github:

![empezando ejemplo 3](https://user-images.githubusercontent.com/91874629/153848139-d4a6a30e-cd7f-4af2-81b7-e4f1bd77e724.png)

#### Editamos el archivo readme.md

#### Lo subimos al area stage y hacemos commit:

![stage y commit](https://user-images.githubusercontent.com/91874629/153849153-5ef9fcb0-2cff-4d71-be71-2860c9ad07d7.png)

#### Para finalizar un push:

![push](https://user-images.githubusercontent.com/91874629/153849225-3d5d47d7-56be-408e-b67c-7425cd214d40.png)

#### En github voy a fusionar las dos ramas: 

![merge](https://user-images.githubusercontent.com/91874629/153849389-3736f131-1eac-4314-abb3-2e7562dc6091.png)
