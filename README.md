# Script de Automatização de Organização de Arquivos.
Este script em PowerShell foi desenvolvido para automatizar o processo de organização de arquivos em uma determinada pasta, movendo-os para pastas de destino com base em suas extensões. Ele é útil para categorizar e ordenar diferentes tipos de arquivos de forma eficiente.

## Funcionalidades do Script.
- Definição de Caminhos de Origem e Destino:
  O script permite definir os caminhos das pastas de origem e destino, onde os arquivos serão organizados.
- Listagem de Arquivos na Pasta de Origem:
  Todos os arquivos na pasta de origem são listados para posterior processamento.
- Movimentação de Arquivos para Pastas de Destino Correspondentes:
  Para cada arquivo na pasta de origem, o script determina sua extensão e o move para a pasta de destino correspondente, com base na extensão do arquivo.
  Os arquivos são categorizados em Textos, Imagens, PDFs ou Outros, conforme suas extensões.

## Como Utilizar o Script.
- Pré-Requisitos: PowerShell no Windows 10.
- Configuração dos Caminhos: Antes de executar o script, certifique-se de definir os caminhos corretos das pastas de origem e destino no início do script, conforme necessário.
Execução do Script:
- Após configurar os caminhos, execute o script PowerShell no Windows 10.
- Resultado: O script irá mover os arquivos da pasta de origem para as pastas de destino correspondentes, organizando-os de acordo com suas extensões.
![printss](https://github.com/matheus3pires/Terceira-Atividade-de-Automacao-ADS1231-Devops/assets/87993331/988b42b3-417f-46da-91c9-b023873d44a7)

## Estrutura do Projeto.
- Origem: Pasta onde os arquivos a serem organizados estão localizados.
- Destino:
   - Textos: Pasta de destino para arquivos de texto (extensões .txt, .doc, .docx).
   - Imagens: Pasta de destino para arquivos de imagem (extensões .jpg, .jpeg, .png, .gif).
   - PDFs: Pasta de destino para arquivos PDF (extensão .pdf).
   - Outros: Pasta de destino para arquivos com extensões diferentes das mencionadas acima.
![imagem](https://github.com/matheus3pires/Terceira-Atividade-de-Automacao-ADS1231-Devops/assets/87993331/e6b97827-51af-482e-a746-3ebe2beb842f)

## Instruções de Uso Docker
1. Navegue para o Diretório do Projeto.
2. Construa a Imagem Docker:
   
        docker build -t terceira-atividade . 
       
3. Execute o Container Docker:
   
        docker run -it terceira-atividade 
       
![imagem (2)](https://github.com/matheus3pires/Terceira-Atividade-de-Automacao-ADS1231-Devops/assets/87993331/64390968-ef91-47df-bdb1-b653f6d7268b)



## Minhas Redes.
Fique conectado para mais novidades e atualizações. Não hesite em entrar em contato!
 
- Linkedin: [linkedin.com/in/matheuspiress](https://www.linkedin.com/in/matheuspiress/)
