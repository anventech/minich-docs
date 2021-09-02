# Funciones

Funciones de la aplicación.

## Contactos

Los contactos son una de las funciones más usadas en la aplicación, ya que estos se asemejan a los de un teléfono.

Los comandos relacionados con los contactos son:

- `contacts`
  - Para ver la lista de contactos o información de un contacto específico.
- `addContact`
  - Para añadir un nuevo contacto.
- `removeContact`
  - Para eliminar un contacto.

!> Ten en cuenta que si no se especifica el argumento **[Nombre del cliente]**, los cambios a los contactos se harán en el cliente actual.

## Sistema de "último chat"

Cada vez que recibes un nuevo mensaje, independientemente del chat o modo en el que estés, la ID de ese chat se guarda como el "último chat", esto es muy útil a la hora de cambiar entre chats.

## Cambiar entre chats

Puedes cambiar entre chats rápidamente usando el comando `chat`, este comando tiene un argumento obligatorio, la ID del chat.

Si no te recuerdas de la ID del chat de la persona a la que le vas a escribir, pero sí la tienes en tus contactos, entonces solo inserta el nombre del contacto (exactamente como lo guardaste al usar el comando `addContact`) junto con el comando `chat`, así: `chat Anventec`



En caso de que sí recuerdes la ID del chat, haz lo mismo que con el contacto solo que cambias el nombre del contacto por la ID, así: `chat 123456789012345678`



Dentro de la aplicación puede obtener información más detallada los comandos usando el comando `help [Nombre del comando]`