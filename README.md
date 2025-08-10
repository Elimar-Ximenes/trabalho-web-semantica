# Trabalho Web Semântica

## Como realizar o mapeamento

1. **Baixar o arquivo JAR do RMLMapper**  
   - Acesse: [RMLMapper Java Releases](https://github.com/RMLio/rmlmapper-java/releases)  
   - Baixe a versão mais recente (no momento, estou utilizando a **v7.3.3**).

2. **Executar o mapeamento**  
   - Utilize o arquivo `.jar` baixado, junto com o arquivo de mapeamento (`.ttl`) e defina o nome e extensão do arquivo de saída.
   - Os arquivos de triplas presentes neste repositório foram gerados com os seguintes comandos:

   ```bash
   java -jar rmlmapper-7.3.3-r374-all.jar -m spotify_mapping_albuns.ttl -o spotify_output_albuns.trig -s trig
   java -jar rmlmapper-7.3.3-r374-all.jar -m spotify_mapping_artistas.ttl -o spotify_output_artistas.trig -s trig
   java -jar rmlmapper-7.3.3-r374-all.jar -m spotify_mapping_tracks.ttl -o spotify_output_tracks.trig -s trig
