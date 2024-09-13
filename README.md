## Patrones arquitectónicos

### Modelo Vista Controlador (MVC)

![1](https://github.com/user-attachments/assets/4e2bfce3-06b4-41cc-a780-688183c2ca93)

#### Modelo (Model):

Representa la lógica de negocio y los datos de la aplicación. Es responsable de gestionar los datos y la interacción con la base de datos o cualquier otra fuente de información.

#### Vista (View):

Representa la interfaz gráfica de usuario (GUI). Es lo que el usuario ve y con lo que interactúa. La vista muestra los datos proporcionados por el modelo.

#### Controlador (Controller):

Actúa como intermediario entre el modelo y la vista. Maneja las solicitudes del usuario, procesa la lógica de negocio y actualiza tanto el modelo como la vista.

### Modelo Vista Presentador (MVP)

![modelo-vista-controlador-3](https://github.com/user-attachments/assets/51e5118d-d3ee-47cd-8ce3-28680933d038)

#### Modelo (Model):

- Representa la lógica de negocio y los datos de la aplicación.

- Es responsable de gestionar los datos y la interacción con la base de datos u otras fuentes de información.

#### Vista (View):

- Representa la interfaz gráfica de usuario (GUI).

- Muestra los datos proporcionados por el modelo y recibe órdenes de usuario.

#### Presentador (Presenter):

- Actúa como intermediario entre el modelo y la vista.

- Maneja las solicitudes del usuario, procesa la lógica de negocio y actualiza tanto el modelo como la vista.

### Modelo Vista ViewModel (MVVM)

![mvvm (1)](https://github.com/user-attachments/assets/4d46362f-f5d4-4697-a274-7f27ce78192d)

#### Modelo:

Representa la lógica de negocio y los datos.

#### Vista:

Es la interfaz gráfica de usuario (GUI) que muestra los datos al usuario.

#### ViewModel:

Actúa como intermediario entre la Vista y el Modelo, permitiendo que la interfaz visual sea independiente de la lógica del negocio.


## Principales Patrones de diseño

### Creacionales

#### Singleton

- Su objetivo principal es garantizar que una clase tenga exactamente una instancia y proporcionar un punto de acceso global a esa instancia.

### Estructurales

#### Adapter

- Su objetivo principal es transformar una interfaz en otra, permitiendo que una clase que no podría utilizar la primera haga uso de ella a través de la segunda.

### De comportamiento

#### Observer

- Su objetivo principal es establecer una dependencia uno a muchos entre objetos, de manera que cuando un objeto (llamado sujeto) cambia su estado, notifica automáticamente a todos sus observadores.
