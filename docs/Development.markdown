## SpoutBreeze Manager

```
gradle bootRun
```

## SpoutBreeze Agent
```
gradle bootRun
```

## SpoutBreeze Broadcaster
```
./build.sh
```

## SpoutBreeze Selenoid

```
./run.sh
```

## SpoutBreeze Player

## SpoutBreeze Extender

## SpoutBreeze Interactor
```
gradle run
```

## SpoutBreeze Web

## RabbitMQ management console

http://spoutbreeze.test:15672/

### Create a new database migration
```bash
vendor/bin/phinx create AddColumnsToAgent
```

### Run database migration
```bash
vendor/bin/phinx migrate
```

### Format the PHP code
```bash
vendor/bin/./php-cs-fixer fix --allow-risky=yes
```
