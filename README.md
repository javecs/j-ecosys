# Javaのエコシステムを紹介します。

## 環境準備
- これから必要なツールとかを簡単にインストールするために[SDKMAN!](http://sdkman.io/install.html)をインストールします。
  ```
  $ curl -s "https://get.sdkman.io" | bash
  $ source "$HOME/.sdkman/bin/sdkman-init.sh"
  ```

- [Java](http://www.oracle.com/technetwork/java/javase) (8u121)
  ```
  $ sdk install java 8u121
  ```

- [Gradle](https://gradle.org/) (3.4.1)
  ```
  $ sdk install gradle 3.4.1
  ```

- [Maven](https://maven.apache.org/) (3.3.9)
  ```
  $ sdk install maven 3.3.9
  ```

- [Kotlin](https://kotlinlang.org/) (1.1.1)
  ```
  $ sdk install kotlin 1.1.1
  ```

- [Spring Boot](http://projects.spring.io/spring-boot/) (1.5.2.RELEASE)
  ```
  $ sdk install springboot 1.5.2.RELEASE
  ```

- ソースコードを書いたり、コンパイルしたりするために、[IntelliJ IDEA](https://www.jetbrains.com/idea/#chooseYourEdition)をインストールします。

## 動作確認
- 必要なツールがインストールできたのかを確認するために、[簡単なアプリ](https://github.com/javecs/j-ecosys-codes-demo)を実行して見ます。
  ```
  $ git clone https://github.com/javecs/j-ecosys-codes-demo.git
  $ cd j-ecosys-codes-demo
  $ gradle bootRun
  ```
- ブラウザーで、[localhost:8080](http://localhost:8080/)をアクセスします。
![ようこそ](http://i.imgur.com/LhNHfLo.png)
- `ようこそ`のボタンを押して、何かのメッセージが表示できたら、環境準備はOKです。

