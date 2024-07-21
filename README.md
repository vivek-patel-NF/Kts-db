# Kts-db
---
| Parameter               | Description                                                                                                           |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------|
| authSource              | The database that holds the user's credentials. Default is the database specified in the URI path or `admin` if none. |
| authMechanism           | Specifies the authentication mechanism to use (e.g., `SCRAM-SHA-1`, `SCRAM-SHA-256`, `MONGODB-X509`).                 |
| ssl or tls              | Enables SSL/TLS for the connection (`true` or `false`).                                                               |
| tlsCAFile               | Specifies the file containing the certificate authority certificates.                                                 |
| tlsCertificateKeyFile   | Specifies the client certificate file.                                                                                |
| tlsAllowInvalidCertificates | Allows invalid certificates when connecting (`true` or `false`).                                                 |
| replicaSet              | The name of the replica set to connect to.                                                                            |
| readConcernLevel        | Specifies the read concern level (`local`, `majority`, `linearizable`, `available`).                                   |
| w                       | Specifies the write concern level (`0`, `1`, `majority`, `<tag set>`).                                                |
| wtimeoutMS              | Specifies the time limit for write operations in milliseconds.                                                        |
| journal                 | Enables or disables journaling for write operations (`true` or `false`).                                              |
| maxStalenessSeconds     | Specifies the maximum replication lag in seconds.                                                                     |
| compressors             | Specifies the compressors to use (`snappy`, `zlib`, `zstd`).                                                          |
| zlibCompressionLevel    | Specifies the level of compression to use when using `zlib` (from `-1` to `9`).                                       |
| socketTimeoutMS         | Specifies the socket timeout in milliseconds.                                                                         |
| serverSelectionTimeoutMS | Specifies the timeout in milliseconds to select a server.                                                           |
| localThresholdMS        | Specifies the local threshold in milliseconds.                                                                        |
| heartbeatFrequencyMS    | Specifies the frequency in milliseconds for the client to send heartbeats to the server.                              |
| minPoolSize             | Specifies the minimum number of connections in the connection pool.                                                   |
| maxIdleTimeMS           | Specifies the maximum idle time for a connection in milliseconds.                                                     |
| maxConnecting           | Limits the number of simultaneous connection attempts.                                                                |
| appName                 | Specifies an application name to associate with the connection.                                                       |
