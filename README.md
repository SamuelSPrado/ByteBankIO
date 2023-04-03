# ByteBankIO
Testes utilizando a manipulação de arquivos externos para contro e criação de novos objetos.

Esse projeto é utilizado para realizar os testes trabalhando com arquivos com o C#. Como o computador interpreta e trabalha com o fluxo de dados.

Nesse teste você verá a utilização de uma classe (FileStream)

Definição: Conforme os Documentos do C# ele "Fornece um Stream para um arquivo, dando suporte a operações de leitura e gravação síncronas e assíncronas.
Herança Object -> Stream -> FileStream".

Você também verá a utilização do unum "FileMode.Open" - O FileMode específica como nosso sistema operacional deve abrir o arquivo.

public enum FileMode
{
  CreateNew = 1,
  Create = 2,
  Open = 3,
  OpenOrCreate = 4,
  Truncate = 5,
  Append = 6
}
