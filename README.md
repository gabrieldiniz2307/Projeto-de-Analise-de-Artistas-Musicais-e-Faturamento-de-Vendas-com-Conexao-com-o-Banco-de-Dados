O banco de dados de  Chinook tem 11 tabelas da seguinte maneira:

employees A tabela armazena dados do funcionário, como ID, sobrenome, nome, etc. Ele também tem um campo nomeado para especificar quem se reporta a quem.ReportsTo
customers A tabela armazena dados do cliente.

invoices & invoice_items Tabelas: essas duas tabelas armazenam dados de faturas. A tabela armazena os dados do cabeçalho da fatura e a tabela armazena os dados dos itens de linha da fatura.invoicesinvoice_items
 artists A tabela armazena dados do artista. É uma tabela simples que contém o id e o nome.

 albums A tabela armazena dados sobre uma lista de faixas. Cada álbum pertence a um artista. No entanto, um artista pode ter vários álbuns.

 media_types A tabela armazena tipos de mídia, como áudio MPEG e arquivos de áudio AAC.
 genres mesa armazena tipos de música como rock, jazz, metal, etc.

 tracks tabela armazena os dados das músicas. Cada faixa pertence a um álbum.

 playlists & playlist_track Tabelas: a tabela armazena dados sobre listas de reprodução. Cada lista de reprodução contém uma lista de faixas. Cada faixa pode pertencer a várias listas de reprodução. A relação entre as tabelas e é de muitos para muitos. A tabela é usada para refletir essa relação.playlists playlists tracks playlist_track
