# Digital Signature PDF Tool

Este projeto é uma aplicação que utiliza a biblioteca [iText](https://itextpdf.com/) para adicionar assinaturas digitais a arquivos PDF. Ele foi desenvolvido para facilitar a integração de funcionalidades de assinatura digital em aplicações.

## 🚀 Funcionalidades

- Assinatura digital de arquivos PDF.
- Validação de assinaturas existentes em PDFs.
- Suporte para diferentes tipos de certificados digitais.

## 🛠️ Tecnologias Utilizadas

- **C#**: Linguagem principal.
- **iText**: Biblioteca utilizada para manipulação e assinatura de PDFs (licenciada sob AGPL).
- **BouncyCastle**: Biblioteca adicional para criptografia.

## 📄 Licença

Este projeto utiliza a biblioteca iText sob a licença **AGPL (Affero General Public License)**. Isso significa que:

1. Todo o código-fonte deste projeto está disponível publicamente.
2. Qualquer modificação feita neste projeto também deve ser disponibilizada publicamente sob a licença AGPL.
3. Qualquer pessoa que utilizar este software, mesmo acessando-o remotamente (por exemplo, via uma API ou aplicação web), tem o direito de acessar o código-fonte.

Para mais informações sobre a licença AGPL, consulte o site oficial da [GNU AGPL](https://www.gnu.org/licenses/agpl-3.0.html).

## 📂 Estrutura do Repositório

```plaintext
.
├── src/               # Código-fonte do projeto
├── lib/               # Bibliotecas externas (iText, BouncyCastle, etc.)
├── resources/         # Arquivos de exemplo e certificados
├── LICENSE.md         # Licença AGPL
└── README.md          # Este arquivo


Aqui está um exemplo de um arquivo README.md para um projeto que utiliza o iText para realizar assinaturas digitais em PDFs. O exemplo inclui informações sobre a licença AGPL, instruções de uso e o propósito do projeto.

Você pode personalizá-lo de acordo com as características específicas do seu projeto.

markdown
Copiar código
# Digital Signature PDF Tool

Este projeto é uma aplicação que utiliza a biblioteca [iText](https://itextpdf.com/) para adicionar assinaturas digitais a arquivos PDF. Ele foi desenvolvido para facilitar a integração de funcionalidades de assinatura digital em aplicações.

## 🚀 Funcionalidades

- Assinatura digital de arquivos PDF.
- Validação de assinaturas existentes em PDFs.
- Suporte para diferentes tipos de certificados digitais.

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem principal.
- **iText**: Biblioteca utilizada para manipulação e assinatura de PDFs (licenciada sob AGPL).
- **BouncyCastle**: Biblioteca adicional para criptografia.

## 📄 Licença

Este projeto utiliza a biblioteca iText sob a licença **AGPL (Affero General Public License)**. Isso significa que:

1. Todo o código-fonte deste projeto está disponível publicamente.
2. Qualquer modificação feita neste projeto também deve ser disponibilizada publicamente sob a licença AGPL.
3. Qualquer pessoa que utilizar este software, mesmo acessando-o remotamente (por exemplo, via uma API ou aplicação web), tem o direito de acessar o código-fonte.

Para mais informações sobre a licença AGPL, consulte o site oficial da [GNU AGPL](https://www.gnu.org/licenses/agpl-3.0.html).

## 📂 Estrutura do Repositório

```plaintext
.
├── src/               # Código-fonte do projeto
├── lib/               # Bibliotecas externas (iText, BouncyCastle, etc.)
├── resources/         # Arquivos de exemplo e certificados
├── LICENSE.md         # Licença AGPL
└── README.md          # Este arquivo
⚙️ Como Utilizar
Pré-requisitos
framework 4.6
Certificado digital no formato .pfx ou .p12.
Passos para Assinar um PDF
Clone este repositório:

bash
Copiar código
git clone https://github.com/ti-dgabc/AssinarArquivoPDF.git
cd AssinarArquivoPDF
Compile o projeto:

bash
Copiar código
./gradlew build
Execute o programa fornecendo os argumentos necessários:

📦 Dependências
iText - Biblioteca principal para manipulação de PDFs.
BouncyCastle - Suporte para criptografia.
🌟 Contribuição
Contribuições são bem-vindas! Se você quiser melhorar este projeto, siga os passos abaixo:

Faça um fork do repositório.
Crie um branch para sua feature ou correção: git checkout -b minha-feature.
Envie suas mudanças: git push origin minha-feature.
Abra um Pull Request.
📞 Suporte
Se você tiver dúvidas ou encontrar problemas, entre em contato através da seção de Issues.
