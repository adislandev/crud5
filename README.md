sql
Copiar
Editar
create table nomes (
  id uuid primary key default gen_random_uuid(),
  nome text not null
);
