# time-lembretes-em-python

Para criar lembretes em Python, você pode usar a biblioteca `datetime`. A biblioteca `datetime` permite trabalhar com datas e horários em Python.

Aqui está um exemplo simples de como criar um lembrete para uma data e hora específicas:

```python
import datetime

# Define a data e hora do lembrete
data_hora_lembrete = datetime.datetime(2023, 4, 15, 10, 30)

# Define a mensagem do lembrete    
mensagem_lembrete = 'Reunião com o Dr. Silva'

# Aguarda até a data e hora do lembrete
while datetime.datetime.now() < data_hora_lembrete:
    pass

# Exibe a mensagem do lembrete
print(mensagem_lembrete)
```

Neste exemplo, estamos criando um lembrete para uma reunião com o Dr. Silva em 15 de abril de 2023 às 10h30. Estamos definindo a data e hora do lembrete usando a classe `datetime.datetime`. Em seguida, estamos definindo a mensagem do lembrete como uma string. Depois disso, estamos aguardando até a data e hora do lembrete usando um loop while. Finalmente, estamos exibindo a mensagem do lembrete.

Espero que isso ajude!
