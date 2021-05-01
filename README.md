# Sistema-Compra-de-Jogos

### Entidades:

---

- **Cliente**
    - ID;
    - Nick;
    - Endereço de Cobrança;
    - Biblioteca de Jogos (multivalorado).
    - HERANÇA: **Cliente com assinatura premium**
- **Jogo**
    - FK de distribuidora;
    - ID;
    - Nome;
    - Genero;
    - Classificação Indicativa.
    - Preço
    - Descrição do Jogo (Opcional)
    - DLC (opcional)

- **Estúdio criador do jogo/distribuidora**
    - CNPJ;
    - Nome;
    - lista de jogos da companhia (?)

### Relacionamentos

---

- Cliente Compra Jogo de Distribuidora; so botar na biblioteca
- Cliente é amigo de N Clientes; lista de amigos
- Distribuidora é Dona do Jogo; so botar dentro de distribuidora
- Cliente Y compra jogo de Distribuidora para Cliente X.