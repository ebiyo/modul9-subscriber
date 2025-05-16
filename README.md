Nama : Arief Ridzki Darmawan

NPM : 2306210115

Kelas : A

---
## 1.
### > Apa itu amqp?
AMQP (Advanced Message Queuing Protocol) adalah protokol messaging yang digunakan untuk komunikasi antara beberapa sistem menggunakan message queues dan sering digunakan pada arsitektur event-driven atau microservices. Sifatnya adalah asinkronus.

### > Apa yang dimaksud dengan ```guest:guest@localhost:5672```? siapa guest pertama dan kedua, dan buat siapa ```localhost:5672``` ini?
* guest pertama => username (defaultnya guest)
* guest kedua => password (defaultnya juga guest)
* localhost => alamat host AMQP, localhost berarti servernya di mesin yang sama
* 5672 => port number yang digunakan AMQP (RabbitMQ secara default listen ke port 5672)
