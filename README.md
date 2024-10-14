**Script de Envio de E-mail via SMTP**

Este é um script simples em Python que permite o envio de e-mails usando o protocolo SMTP. Ele utiliza a biblioteca smtplib para se conectar a um servidor SMTP e enviar um e-mail para o destinatário desejado.

Funcionalidades

	•	Envia e-mails de forma automática
	•	Possibilidade de personalizar o remetente, destinatário, assunto e corpo do e-mail
	•	Compatível com o servidor SMTP do Gmail

Requisitos

	•	Python 3.x
	•	Acesso a uma conta de e-mail Gmail
	•	Biblioteca smtplib (inclusa no Python por padrão)

Instalação

Não é necessário instalar nenhuma dependência adicional, pois o script utiliza apenas bibliotecas nativas do Python.

Como Usar:

	1.	Clone este repositório ou faça o download do arquivo.
	2.	No terminal ou prompt de comando, navegue até o diretório do script.
	3.	Execute o script:

python nome_do_arquivo.py


	4.	Insira as informações solicitadas:
	•	E-mail Remetente: E-mail da conta que será usada para enviar a mensagem.
	•	E-mail Destinatário: E-mail do destinatário da mensagem.
	•	Assunto: O assunto do e-mail.
	•	Mensagem: O corpo do e-mail.
	5.	O script solicitará que você insira a senha do e-mail remetente. Use uma senha de aplicativo se estiver utilizando Gmail.

Exemplo

EMAIL REMETENTE: seuemail@gmail.com
EMAIL DESTINATÁRIO: destinatario@gmail.com
ASSUNTO: Teste de Envio
MENSAGEM: Este é um e-mail de teste enviado via Python!

Atenção!

	•	Se estiver usando Gmail, você precisa configurar seu e-mail para aceitar “Aplicativos Menos Seguros” ou utilizar uma senha de aplicativo.

Contribuição

Sinta-se à vontade para abrir issues e enviar pull requests para melhorar este projeto.
