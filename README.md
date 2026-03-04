# django_login_facebook 🔐📘

Projeto Django desenvolvido para **estudar e implementar autenticação social utilizando login com Facebook**.

A aplicação demonstra como integrar o **sistema de autenticação do Django** com **OAuth do Facebook**, permitindo que usuários façam login utilizando suas contas da rede social.

Esse tipo de autenticação é muito utilizado em aplicações modernas para simplificar o processo de cadastro e login dos usuários.

---

# 🎯 Objetivo do Projeto

O objetivo deste projeto é demonstrar:

- Integração de **login social com Facebook**
- Uso de **OAuth em aplicações Django**
- Implementação de **autenticação segura baseada em tokens**
- Redução de fricção no processo de cadastro de usuários

Essa abordagem é muito utilizada em plataformas web que desejam permitir:

✔️ Login rápido  
✔️ Integração com redes sociais  
✔️ Redução de formulários de cadastro  
✔️ Melhor experiência do usuário  

---

# 🧰 Tecnologias Utilizadas

- Python
- Django
- OAuth 2.0
- Facebook Login API
- HTML
- CSS

---

# ⚙️ Como funciona a autenticação

O fluxo de autenticação segue o padrão **OAuth 2.0**:

1. Usuário clica em **Login com Facebook**
2. O usuário é redirecionado para o **Facebook**
3. O Facebook solicita autorização do usuário
4. Após autorização, o Facebook retorna um **token de acesso**
5. O Django valida o token e autentica o usuário na aplicação

Esse fluxo evita que a aplicação tenha acesso à senha do usuário.

---
