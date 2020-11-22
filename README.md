# React Starter Kit in TypeScript

## アプリケーションの起動方法(Dockerを使用する場合)

    $ wget https://github.com/DiveIntoHacking/react-starter-kit-in-javascript-with-node-v12.18.4/archive/v1.1.tar.gz
    $ tar zxvf v1.1.tar.gz
    $ cd react-starter-kit-in-javascript-with-node-v12.18.4-1.1
    $ touch .bash_history
    $ docker-compose build
    $ docker-compose run --rm app yarn install
    $ docker-compose up
