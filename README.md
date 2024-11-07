# Funds-Validator

**Funds-Validator** – це Java-програма, що перевіряє достатність коштів на рахунку для здійснення покупки. Якщо коштів достатньо, програма здійснює покупку і показує залишок. Якщо ні, виводиться повідомлення про недостатність коштів.

- **Main.java**: містить клас `Main` для основної логіки програми і клас `FundsException` для обробки помилок.

## Використання

1. Запустіть програму.
2. Програма покаже баланс (1000 USD за замовчуванням).
3. Введіть суму покупки.
   - Якщо коштів вистачає, покупка буде здійснена, і програма покаже новий баланс.
   - Якщо коштів недостатньо, буде виведено повідомлення "Insufficient funds!"

