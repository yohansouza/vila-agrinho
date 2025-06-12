# Vila Agrinho
#agrinho2025

## Introdução

Olá, caro jogador.

Seja muito bem-vindo ao Vila Agrinho!  
Nesta jornada, você descobrirá a importante conexão entre o campo e a cidade, colaborando com os moradores locais.

Sua missão é clara: procure os fazendeiros nas hortas, receba as sementes e plante-as (pressionando **ENTER**) para acompanhar o crescimento e a colheita dos frutos.

Para acessar sua mochila e verificar seus itens, pressione a tecla **E**.

Para viajar para a cidade e voltar, pressione a tecla **C**.  
Ao ir para a cidade, suas sementes desaparecerão do inventário, abrindo espaço para novos itens!

**Atenção:** Ao retornar para o campo, o pacote de trigo e o suco de morango também serão deixados para trás, pois são produtos para a cidade.

Na cidade, procure os NPCs do Mercado e da Indústria e aperte **Q** para entrar nesses locais.

Na Indústria, use a tecla **2** para transformar o trigo em pacotes de trigo.

Na Indústria, use a tecla **3** para transformar morangos em suco de morango.

No Mercado, pressione **T** para vender Pacotes de Trigo e **M** para vender Suco de Morango, e acumule dinheiro!

**O seu objetivo é alcançar 30 de dinheiro!**

Boa sorte — e aproveite sua aventura no mundo de Agrinho!

---

## Como Rodar
1. Clone este repositório.
2. Abra o arquivo `index.html` em um navegador que suporte p5.js.
3. Divirta-se!

---

## Controles
- **WASD** para mover o personagem.
- **E** para abrir/fechar o inventário (mochila).
- **ENTER** para plantar sementes.
- **C** para viajar entre campo e cidade.
- **Q** para entrar nos NPCs Mercado e Indústria na cidade.
- **2** para transformar trigo em pacotes de trigo na Indústria.
- **3** para transformar morangos em suco de morango na Indústria.
- **T** para vender Pacotes de Trigo no Mercado.
- **M** para vender Suco de Morango no Mercado.
- Clique no botão **Start** no menu para iniciar o jogo.

---

## Regras do Jogo

### Plantio
- O personagem só pode plantar dentro das hortas delimitadas por bordas cinzas, próximas dos NPCs.
- Morango só pode ser plantado na horta do NPC 1 (área superior).
- Trigo só pode ser plantado na horta do NPC 2 (área inferior).
- Se tentar plantar fora da horta ou na área errada, aparece a mensagem:
  - *"Você não pode plantar aqui, apenas na horta!"* ou
  - *"Plantar essa semente aqui não é permitido!"*.
- Ao plantar, o pacote de sementes usado desaparece do inventário até a colheita.
- Se tentar plantar antes do crescimento, aparece a mensagem: *"As plantas estão crescendo, espere!!"*.

### Crescimento e Colheita
- As plantas demoram 4 segundos para crescer.
- Após o tempo, o jogador pode colher e recebe 10 unidades da planta.
- O inventário armazena sem limite de unidades, mas se estiver cheio, aparece *"Inventário cheio"* e a colheita não é adicionada.
- Após colher, é possível plantar novamente naquela área.

### Inventário
- Mostra a quantidade atual de morangos, trigo, pacotes de trigo e suco de morango.
- Pode abrir e fechar com a tecla **E**.
- Permite selecionar qual semente usar para plantar.

### Progressão
- O objetivo é ajudar os NPCs, plantar, colher, transformar produtos na Indústria e vender no Mercado.
- O jogo termina quando o jogador alcançar 30 de dinheiro.

---

## Tela de Menu e Loading
- O jogo começa com uma tela de menu com botão de Start.
- Após clicar Start, aparece uma tela de loading por 15 segundos.
- Depois, o jogo inicia normalmente.

---

## Imagens e Assets
- Personagens, NPCs, cenário e itens usam imagens específicas (`personagem.png`, `npc1.png`, `cidade.png`, etc).
- A escala do jogo está ajustada para facilitar a visualização.

---

## Tecnologias
- Feito em JavaScript com a biblioteca p5.js.
- Ideal para estudos e projetos de games simples.

---

Desenvolvido por Yohan.

---

Valeu por conferir o Vila Agrinho! Bora plantar, colher e fazer a vila crescer!

