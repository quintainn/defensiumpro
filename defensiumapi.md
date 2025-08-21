# DEFENSIUM SERVICE

## Database

<details>

<summary>Acesso ao Banco de Dados</summary>

```javaDEFENSIUM_
spring.datasource.url=jdbc:postgresql://db.bvckmqcqkthmfaadyzub.supabase.co:5432/postgres
spring.datasource.username=postgres
spring.datasource.password=ZGVmZW5zaXVtc2VydmljZQ==
```
<br/>
</details>

<details>

<summary>Dados do Servidor</summary>

```ruby
export DEFENSIUM_DESENVOLVIMENTO_DATABASE_HOST=db.bvckmqcqkthmfaadyzub.supabase.co
export DEFENSIUM_DESENVOLVIMENTO_DATABASE_NAME=postgres?sslmode=require&channel_binding=require
export DEFENSIUM_DESENVOLVIMENTO_DATABASE_PORT=5432
export DEFENSIUM_DESENVOLVIMENTO_DATABASE_USERNAME=postgres
export DEFENSIUM_DESENVOLVIMENTO_DATABASE_PASSWORD=ZGVmZW5zaXVtc2VydmljZQ==
```
</details>

<details>

<summary>Modelagem de Dados</summary>

```sql
drop table if exists databasechangelog cascade;
drop table if exists databasechangeloglock cascade;
drop table if exists tb_perfil cascade;
select * from databasechangelog order by dateexecuted desc;
```

</details>

## Protótipos

## Arquitetura