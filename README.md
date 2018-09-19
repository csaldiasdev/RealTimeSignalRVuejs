# RealTime / SignalR / Vuejs

Este proyecto trata de un backend hecho en C# sobre ASP.Net Core 2 y un webapp hecho con Vuejs-2.

La finalidad de este proyecto es demostrar como integrar el cliente javascript de SignalR dentro de una webapp realizada con Vuejs, para así poder recibir los mensajes provenientes del servidor y almacenarlos dentro del state del webapp usando Vuex.

Actualmente el servidor tiene 5 tipos de mensajes que se enviaran de forma aleatoria cada 5 segundos, los mensajes serán enviados a todos los clientes que se conecten al servidor de forma simultanea.

![screen shot 2018-09-19 at 6 42 09 pm](https://user-images.githubusercontent.com/10968602/45784590-add24400-bc3f-11e8-9123-e11928a3e3eb.png)
