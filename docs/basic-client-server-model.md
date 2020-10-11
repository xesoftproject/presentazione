Client-Server model
===================

Una versione *molto* *molto* *base* di quello che potrebbe essere il modello
client server.

Nello specifico penso sia più corretto utilizzare un approccio classico solo
per il caricamento dell'html e delle risorse (css, js, .gltf...).

La comunicazione dei comandi da eseguire (movimento pezzi) è più "naturale"
se avviene su tecnologia push (websocket, webcomet, quella roba là)

![](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUgQXJjaGl0ZXR0dXJhIHBhcnRpdGEgVXNlciBWUyBBSQoKYWN0b3IADQUKVXNlci0-QnJvd3NlcjogIiJhemlvbmUiIChhdWRpbywgbW92aW1lbnRvLi4uKSIKACMHLT5TZXJ2ZXI6IG5vdGlmaWNhICJjYXZhbGxvIGluIEEzIgoAGwYtPitJQTogVUNJCklBLT4tAC4JZXh0IG1vdmUAHwkAewkASAphbGZpZXJlIGluIEIyAHELVQCBJwV1cGRhdGUgdWkKCg&s=default)

Per l'IA, storicamente esistono "chess engine" - guardando su wikipedia sembra
che https://stockfishchess.org/ al momento sia il migliore.

Per parlarci sembra ci siano vari modi, ma lo standard dovrebbe essere
https://en.wikipedia.org/wiki/Universal_Chess_Interface.

Vedo che esistono wrapper, ad esempio c'è https://python-chess.readthedocs.io
in python, ma magari c'è altro.
