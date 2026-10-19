# Meu Financeiro — Android em Java

App de controle financeiro com:
- Saldo automático
- Receitas e despesas
- Categorias
- Lista de lançamentos
- Editar e excluir
- Banco de dados Room (salva no celular)

## Como compilar
1. Instale o Android Studio.
2. Abra a pasta `MeuFinanceiro`.
3. Espere o Gradle baixar as dependências.
4. Conecte o celular com depuração USB ou use um emulador.
5. Clique em **Run ▶**.

## Estrutura
- `Transaction.java`: modelo do lançamento
- `TransactionDao.java`: consultas do banco
- `AppDatabase.java`: banco Room
- `MainActivity.java`: lista e saldo
- `AddTransactionActivity.java`: cadastrar/editar
