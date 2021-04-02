# hello-word-erlang

- step 1

```
sudo yum install epel-release
wget https://packages.erlang-solutions.com/erlang-solutions-1.0-1.noarch.rpm
sudo rpm -Uvh erlang-solutions-1.0-1.noarch.rpm
```

- step 2

```
sudo yum install erlang
sudo yum install esl-erlang
```

- step 3

```
erlc helloworld.erl
```

- step 4

```
erl -noshell -s helloworld start -s init stop
```
