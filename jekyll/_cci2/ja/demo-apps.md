---
layout: classic-docs
title: "Supported Languages Guide"
short-title: "サポートされている言語"
description: "一般的な言語による CircleCI サンプルアプリケーションの一覧"
categories:
  - language-guides
order: 0
---

Code that builds on Linux or iOS will generally build on CircleCI 2.0. We’ve created several demo applications in various languages, so you can learn by example from an app written in the same language as your application. 以下に挙げた各言語については、GitHub のパブリックリポジトリと関連ガイドを公開しています。 それぞれをフォークし、内容を確認してみてください。

| Language Guide                                                                                                        | Framework    | GitHub Repo Name                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| [Android]({{ site.baseurl }}/2.0/language-android/){:target="_blank"}                                                 | Gradle       |                                                                                                                                        |
| [Android](https://github.com/CircleCI-Public/circleci-demo-react-native/blob/master/README.md){:target="_blank"}      | React Native | [circleci-demo-react-native](https://github.com/CircleCI-Public/circleci-demo-react-native){:target="_blank"}                          |
| [Clojure]{:target="_blank"}                                                                                           | Luminus      | [circleci-demo-clojure-luminus](https://github.com/CircleCI-Public/circleci-demo-clojure-luminus){:target="_blank"}                    |
| [Crystal]({{ site.baseurl }}/2.0/language-crystal/)                                                                   | Kemal        | [circleci-demo-crystal](https://github.com/CircleCI-Public/circleci-demo-crystal)                                                      |
| C                                                                                                                     | -            | [parallel-compile-circleci](https://github.com/eddiewebb/parallel-compile-circleci/blob/master/.circleci/config.yml){:target="_blank"} |
| [Elixir]{:target="_blank"}                                                                                            | Phoenix      | [circleci-demo-elixir-phoenix](https://github.com/CircleCI-Public/circleci-demo-elixir-phoenix){:target="_blank"}                      |
| [Go]{:target="_blank"}                                                                                                | Go           | [circleci-demo-go](https://github.com/CircleCI-Public/circleci-demo-go){:target="_blank"}                                              |
| [iOS]{:target="_blank"}                                                                                               | Xcode        | [circleci-demo-ios](https://github.com/CircleCI-Public/circleci-demo-ios){:target="_blank"}                                            |
| [iOS](https://github.com/CircleCI-Public/circleci-demo-react-native/blob/master/README.md){:target="_blank"}          | React Native | [circleci-demo-react-native](https://github.com/CircleCI-Public/circleci-demo-react-native){:target="_blank"}                          |
| [macOS]({{ site.baseurl }}/2.0/hello-world-macos){:target="*blank*"}                                                  | MacOS        | [circleci-demo-macos](https://github.com/CircleCI-Public/circleci-demo-macos){:target="_blank"}                                        |
| [Java]{:target="_blank"}                                                                                              | Spring       | [circleci-demo-java-spring](https://github.com/CircleCI-Public/circleci-demo-java-spring){:target="_blank"}                            |
| [Java]({{ site.baseurl }}/2.0/language-java-maven/){:target="_blank"}                                                 | Maven        | [circleci-demo-java-spring-tree-maven](https://github.com/CircleCI-Public/circleci-demo-java-spring/tree/maven){:target="_blank"}      |
| [JavaScript]{:target="_blank"}                                                                                        | React        | [circleci-demo-javascript-express](https://github.com/CircleCI-Public/circleci-demo-javascript-express){:target="_blank"}              |
| [PHP]{:target="_blank"}                                                                                               | Laravel      | [circleci-demo-php-laravel](https://github.com/CircleCI-Public/circleci-demo-php-laravel){:target="_blank"}                            |
| [Python]{:target="_blank"}                                                                                            | Django       | [circleci-demo-python-django](https://github.com/CircleCI-Public/circleci-demo-python-django){:target="_blank"}                        |
| [Python]({{ site.baseurl }}/2.0/project-walkthrough/){:target="_blank"}                                               | Flask        | [circleci-demo-python-flask](https://github.com/CircleCI-Public/circleci-demo-python-flask){:target="_blank"}                          |
| [React Native](https://github.com/CircleCI-Public/circleci-demo-react-native/blob/master/README.md){:target="_blank"} | React Native | [circleci-demo-react-native](https://github.com/CircleCI-Public/circleci-demo-react-native){:target="_blank"}                          |
| [Ruby and Rails]{:target="_blank"}                                                                                    | Rails        | [circleci-demo-ruby-rails](https://github.com/CircleCI-Public/circleci-demo-ruby-rails){:target="_blank"}                              |
| [Scala]({{ site.baseurl }}/2.0/language-scala/){:target="_blank"}                                                     | sbt          | [samplescala](https://github.com/ariv3ra/samplescala){:target="_blank"}                                                                |
| [Windows]({{ site.baseurl }}/2.0/hello-world-windows/){:target="_blank"}                                              | .NET         | [circleci-demo-windows](https://github.com/CircleCI-Public/circleci-demo-windows/){:target="_blank"}                                   |
{: class="table"}

## サポートされている言語

- Clojure (v1.2.0 以降)
- Elixir (v1.2 以降)
- Go (v1.7 以降)
- Java (Java 8 以降)
- JavaScript (Node.js 4 以降)
- PHP (PHP 5 以降)
- Python (Python 2 以降)
- React Native
- Ruby on Rails (Ruby 2 以降)
- Scala および sbt

C、C#、C++、Clojure、Elixir、Erlang、Go、Groovy、Haskell、Haxe、Java、JavaScript、Node.js、Perl、PHP、Python、Ruby、Rust、Scala、その他多数の言語でプロジェクトをビルドできます。

## 関連項目

最初のビルドを実行する手順については、「[はじめに]({{ site.baseurl }}/ja/2.0/getting-started/)」を参照してください。

[Android]：{{ site.baseurl }}/ja/2.0/language-android/ [Clojure]：{{ site.baseurl }}/ja/2.0/language-clojure/ [Elixir]：{{ site.baseurl }}/ja/2.0/language-elixir/ [Go]：{{ site.baseurl }}/ja/2.0/language-go/ [iOS]：{{ site.baseurl }}/ja/2.0/ios-tutorial/ [Java]：{{ site.baseurl }}/ja/2.0/language-java/ [JavaScript]：{{ site.baseurl }}/ja/2.0/language-javascript/ [PHP]：{{ site.baseurl }}/ja/2.0/language-php/ [Python]：{{ site.baseurl }}/ja/2.0/language-python/ [Ruby on Rails]：{{ site.baseurl }}/ja/2.0/language-ruby/