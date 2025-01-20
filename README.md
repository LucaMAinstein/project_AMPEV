# project_AMPEV
Data Eng Project using DataBricks

1. Run configuration to create datasets (bronze, silver, and gold layers)
2. Bronze Layer:
  a. estabelecimentos load with time_stamp
  b. pedidos load with time_stamp
3. Silver Layer:
  a. definition of a func to add comment to the table (metadata)
  b. left join from 'pedidos' to 'estabelecimentos' to add nome_estabelecimento, email and telefone to each line of 'pedidos'
4. Gold Layer:
  a. gold_table_estabelec: for select total qtt
  b. gold_table_pedidos: compare product performance!
  c. Problem Statement Solution Draft: This approach is the best solution for solving the business problem!
5. Comment:
  a. CAST(value AS format) converts a value into the selected format;
  b. ALWAYS create a log on every code file!
  c. Add a control column!
