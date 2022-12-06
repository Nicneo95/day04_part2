<!-- compile java app -->
javac SocketApp.java
<!-- run server file first -->
java -cp classes SocketApp server 12000 cookie-file.txt
<!-- run client file -->
java -cp classes SocketApp client localhost 12000