# p2p-chord

Запустите сигнальный сервер для peerjs:

```node server/peer-server.js```

Запустите init.html (желательно из браузера Chrome).

Откройте join.html. Чтобы подключиться к DHT введите Node ID из init.html в поле __Connect to a DHT:__

Введите в __Enter message__:
```/dht __DHT-id__ your_message```

Чтобы отправить сообщение пользователю с заданным DHT-id. 
## Функциональность 
* Хранение контактной информации в узлах dht
* Обновление finger-table при подключении новых пиров. 
