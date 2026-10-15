# GORA VIDEO PRO — projeto Android inicial

## Estado atual
Este é um protótipo inicial. Já tem uma interface preta e roxa, escolha de vídeo e pré-visualização. Os botões Cortar, Texto, Áudio, Filtros, Transições e Exportar ainda são marcadores e não executam edição real. Portanto, o APK gerado nesta etapa será apenas uma prévia inicial, não um editor completo.

## Compilar sem computador usando GitHub Actions
1. No navegador do telemóvel, entre em GitHub e crie uma conta, caso ainda não tenha.
2. Crie um repositório novo, por exemplo `gora-video-pro`.
3. Extraia o ZIP do projeto. No GitHub pelo navegador, carregue os ficheiros e pastas do projeto para o repositório, mantendo a estrutura, incluindo a pasta `.github/workflows`.
4. Abra a aba **Actions** do repositório. Se aparecer uma mensagem de autorização para workflows, aceite.
5. Escolha **Build GORA VIDEO PRO APK** e toque em **Run workflow** (ou aguarde a execução automática após enviar os ficheiros).
6. Quando o workflow terminar com sucesso, abra a execução, desça até **Artifacts** e descarregue `GORA-VIDEO-PRO-debug-apk`.
7. Extraia o ZIP descarregado para obter `app-debug.apk` e instale-o no Android. O telemóvel poderá pedir autorização para instalar aplicações desta origem.

Se carregar os ficheiros individualmente pelo navegador for demasiado difícil, use um serviço de GitHub que permita carregar pastas/ficheiros, ou peça ajuda a alguém para fazer apenas o primeiro carregamento do repositório.

## Requisitos do projeto
- Android Gradle Plugin 8.7.3
- Kotlin 2.0.21
- Java 17
- Android SDK 35
- minSdk 23

## Próximas etapas
1. Implementar cortes e divisão reais.
2. Criar linha do tempo e guardar projetos.
3. Implementar texto e faixas de áudio.
4. Implementar exportação MP4.
5. Acrescentar efeitos, transições e ferramentas online de IA.
6. Testar consumo de memória e compatibilidade no Galaxy A21s (3 GB RAM).

O projeto é original e não contém código proprietário do CapCut.
