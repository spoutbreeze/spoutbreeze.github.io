 
## Create a new database migration
```bash
vendor/bin/phinx create AddColumnsToAgent
```

## Run database migration
```bash
vendor/bin/phinx migrate
```

## Format the PHP code
```bash
vendor/bin/./php-cs-fixer fix --allow-risky=yes
```
