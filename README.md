# VR-Sample-Heist
 
# Unity Engine 2022.3.11f1

## Criação do Projeto
Para iniciar o projeto, abra o Unity Hub, selecione "Novo Projeto" e, na aba "Samples", escolha o sample de VR Core.

## Cenário e Assets
O cenário foi desenvolvido utilizando assets da loja Polygon. Os recursos estão disponíveis nos seguintes links:

- [Polygon Heist - Unity Asset Store](https://assetstore.unity.com/packages/3d/environments/urban/polygon-heist-low-poly-3d-art-by-synty-97949)
- [Polygon Heist Pack - Polygon Store](https://syntystore.com/products/polygon-heist-pack?_pos=1&_sid=318b4c2e4&_ss=r)

Adicionamos interações customizadas para aprimorar a experiência no cenário.

## Equipamento VR
O vídeo de gameplay foi gravado utilizando o Oculus Quest 2.

## Repositorio do Git
- [Git](https://github.com/Ddieguin/CG_VR)

# Configuração Mínima para PC de Realidade Virtual (VR)

## Requisitos de Hardware:

### Processador (CPU):
- Intel Core i5-4590 / AMD Ryzen 5 1500X ou equivalente.

### Placa de Vídeo (GPU):
- NVIDIA GTX 1060 / AMD Radeon RX 480 ou equivalente.

### Memória RAM:
- 8 GB de RAM.

### Portas USB:
- Pelo menos uma porta USB 3.0.

### Sistema Operacional:
- Windows 10.

### Espaço de Armazenamento:
- Pelo menos 256 GB de espaço livre no disco rígido ou SSD.

### Conectividade:
- Conexão com a Internet para downloads e atualizações.

### Dispositivo de Realidade Virtual:
- Headset VR compatível com o seu sistema (por exemplo, Oculus Rift, HTC Vive, Valve Index, etc.).

## Observações:
1. Certifique-se de que a placa-mãe suporta os requisitos de hardware, especialmente em termos de portas USB e slots PCIe.
2. Um ambiente de VR pode exigir uma área física adequada para movimentação, dependendo do sistema de rastreamento utilizado pelo headset.
3. Considere também a qualidade do monitor, pois uma experiência de VR é frequentemente espelhada na tela.

Essas são configurações mínimas e podem variar dependendo das aplicações específicas de VR que você pretende usar. Configurações mais robustas proporcionarão uma experiência VR mais suave e com melhor qualidade gráfica.

## Fatores que Afetam o Gasto de Processamento em Aplicações de Realidade Virtual (VR)

1. **Qualidade Gráfica:**
   - Aplicações VR com gráficos mais detalhados e realistas exigirão mais poder de processamento, incluindo resolução de texturas, complexidade dos modelos 3D e efeitos visuais.

2. **Taxa de Quadros (FPS):**
   - Manter uma taxa de quadros alta (geralmente 90Hz ou superior) é crucial para uma experiência VR suave, aumentando a carga no processador e na GPU.

3. **Tipo de Headset VR:**
   - Diferentes headsets VR têm requisitos de sistema variados, com headsets de alta resolução e recursos avançados exigindo mais processamento.

4. **Otimização do Software:**
   - A eficiência do código do software é crucial; aplicações bem otimizadas extraem mais desempenho do hardware disponível.

5. **Interação em Tempo Real:**
   - Interatividades complexas em tempo real, como física avançada, simulações ou detecção de colisão complexa, podem aumentar a carga de processamento.

Dado que nossa aplicação faz uso de modelos 3D com uma quantidade reduzida de polígonos, isso contribui significativamente para alcançarmos uma taxa de quadros (FPS) mais elevada. Isso é crucial em uma aplicação de Realidade Virtual (VR), onde a Game Engine precisa renderizar os dois olhos do usuário para proporcionar a imersão adequada.


# Manual do Usuário - Executável Unity

### Requisitos do Sistema

Antes de começar, certifique-se de que seu sistema atenda aos seguintes requisitos:

- **Sistema Operacional:** Windows 10 / macOS / Linux
- **Placa de Vídeo:** Compatível com DirectX 11 / Metal / OpenGL 4.5
- **Memória RAM:** 8 GB ou mais
- **Espaço em Disco:** 2 GB disponíveis

## Instalação e Configuração

1. **Clone o Repositório:**
   - Abra o terminal ou prompt de comando.
   - Execute o seguinte comando:
     ```bash
     git clone https://github.com/Ddieguin/CG_VR
     ```

2. **Instale o Unity Hub:**
   - Baixe e instale o Unity Hub a partir do site oficial da Unity (https://unity3d.com/unity/whats-new/2020.3.27).

3. **Adicione o Projeto ao Unity Hub:**
   - Abra o Unity Hub.
   - Clique em "Add" e selecione o diretório do projeto clonado.

4. **Verifique a Versão do Unity:**
   - Certifique-se de que o projeto está configurado para a versão correta do Unity. Abra o Unity Hub, selecione o projeto e verifique a versão na guia "Instalado".

5. **Instale as Dependências:**
   - Dependendo do seu projeto, pode ser necessário instalar bibliotecas, pacotes ou assets adicionais. Consulte a documentação do projeto para obter informações específicas.

## Execução do Projeto

Após a configuração inicial, você está pronto para executar o projeto.

1. **Abra o Projeto no Unity:**
   - No Unity Hub, selecione o projeto e clique em "Abrir Projeto".

2. **Configure as Configurações do Projeto:**
   - Verifique e ajuste as configurações do projeto, como resolução, qualidade gráfica, etc.

3. **Inicie a Execução:**
   - Pressione o botão "Play" no canto superior da interface do Unity para iniciar a execução do projeto.

4. **Modo Desenvolvedor:**
   - Se necessário, ative o modo desenvolvedor ou qualquer configuração específica para o desenvolvimento. Consulte a documentação do projeto para obter informações detalhadas.



