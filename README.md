💻 Sistema de Login com CustomTkinter

Este é um projeto simples de interface gráfica desenvolvido em Python usando a biblioteca CustomTkinter. O sistema simula uma tela de login onde o usuário insere um nome de usuário e senha.

📋 Funcionalidades

Interface escura (modo Dark).

Campos para inserir usuário e senha.

Botão de login com verificação simples.

Mensagem de sucesso ou erro ao tentar logar.

✅ Validação

O login só será aceito se:

Usuário: jhonatan

Senha: 123456

Caso contrário, será exibida uma mensagem de erro.

🛠️ Requisitos

Certifique-se de ter o Python instalado. Depois, instale a biblioteca customtkinter com:
pip install customtkinter

▶️ Como executar

Salve o código em um arquivo chamado, por exemplo, login_app.py e execute com:
python login_app.py

🖼️ Imagem (opcional)
![python set](https://github.com/user-attachments/assets/c4da0bfd-f1aa-42d5-9bea-7190a066c213)

📁 Estrutura do Projeto
login_app.py

✍️ Código Fonte (resumo)
if usuario == 'jhonatan' and senha == '123456':
    resultado_login.configure(text='Login feito com sucesso', text_color='green')
else:
    resultado_login.configure(text='Login incorreto', text_color='red')

🔒 Aviso

Este é apenas um exemplo educacional. Não use validação de login assim em aplicações reais. Senhas devem ser sempre criptografadas e armazenadas de forma segura.

[license..txt](https://github.com/user-attachments/files/22187150/license.txt)
MIT License



