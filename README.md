# encrypt_algorithms
Collect open source libraries for all kinds of encryption algorithms


## Java

### SHA-1
#### [apache/commons-codec](https://github.com/apache/commons-codec)

org.apache.commons.codec.digest

##### Methods

```
getSha1Digest
getShaDigest
sha
sha1
sha1Hex
```

##### In Maven

```xml
<!-- https://mvnrepository.com/artifact/commons-codec/commons-codec -->
<dependency>
    <groupId>commons-codec</groupId>
    <artifactId>commons-codec</artifactId>
    <version>1.15</version>
</dependency>
```

#### [google/guava](https://github.com/google/guava)

com.google.common.hash.Hashing

##### Methods

```
sha1
```

##### In Maven

```xml
<dependency>
  <groupId>com.google.guava</groupId>
  <artifactId>guava</artifactId>
  <version>30.1-jre</version>
  <!-- or, for Android: -->
  <version>30.1-android</version>
</dependency>
```

#### MessageDigest

java.security.MessageDigest

##### Methods

```
getInstance("SHA-1")
```

### MD5

#### MessageDigest

java.security.MessageDigest

##### Methods

```
getInstance("SHA-1")
```

#### [apache/commons-codec](https://github.com/apache/commons-codec)

org.apache.commons.codec.digest

##### Methods

```
getMd5Digest
md5
md5Hex
```

##### In Maven

```xml
<!-- https://mvnrepository.com/artifact/commons-codec/commons-codec -->
<dependency>
    <groupId>commons-codec</groupId>
    <artifactId>commons-codec</artifactId>
    <version>1.15</version>
</dependency>
```

#### [google/guava](https://github.com/google/guava)

com.google.common.hash.Hashing

##### Methods

```
md5
```

##### In Maven

```xml
<dependency>
  <groupId>com.google.guava</groupId>
  <artifactId>guava</artifactId>
  <version>30.1-jre</version>
  <!-- or, for Android: -->
  <version>30.1-android</version>
</dependency>
```

### Diffie-Hellman

#### KeyPairGenerator

java.security.KeyPairGenerator

##### Methods

```
getInstance("DH")
```

### RSA

#### KeyPairGenerator

java.security.KeyPairGenerator

##### Methods

```
getInstance("RSA")
```

#### Cipher

javax.crypto.Cipher

##### Methods

```
getInstance("RSA")
```

### DSA

#### KeyPairGenerator

java.security.KeyPairGenerator

##### Methods

```
getInstance("DSA")
```

### ElGamal

#### KeyPairGenerator

java.security.KeyPairGenerator

##### Methods

```
getInstance("ElGamal")
```

