# Parceiros — Tipos Básicos (Tormenta20)

> **Id do módulo:** `tormenta20-parceiros-basicos`
> **Autor:** @xx_.luis._xx
> **Versão:** 1.0.0

Compêndio de **itens de parceiro genéricos** do sistema **Tormenta20**. Reúne todos os tipos do livro básico (**Tormenta20 — Edição Jogo do Ano, p. 260–262**), nas versões **iniciante, veterano e mestre**:

- **12 tipos de parceiro:** Combatente, Guardião, Fortão, Atirador, Perseguidor, Vigilante, Ajudante, Adepto, Magivocador, Médico, Destruidor e Assassino.
- **6 montarias:** Cavalo (e pônei), Cão de Caça, Grifo, Trobo, Lobo-das-Cavernas (e lobo comum) e Lobo-Crocodilo (gorlogg).

São **54 itens**: 12 × 3 + 6 × 3. Os parceiros de campanha ficam no módulo separado **`guerra-artoniana-parceiros`**.

---

## Instalação rápida no Foundry

Em **Add-on Modules → Install Module**, cole isto no campo **URL do Manifesto**:

```
https://github.com/Luisguilhermelr/tormenta20-parceiros-basicos/releases/latest/download/module.json
```

Clique em **Install** e depois ative o módulo em **Gerenciar Módulos**.
O Foundry baixa e atualiza o módulo sozinho a partir dessa URL.

> Repositório: https://github.com/Luisguilhermelr/tormenta20-parceiros-basicos

---
## Instalação manual

1. Feche o Foundry VTT.
2. Copie a pasta `tormenta20-parceiros-basicos` para `Data/modules/`.
3. Abra o Foundry, entre no mundo e ative o módulo em **Configurar Ajustes → Gerenciar Módulos**.
4. Abra o compêndio **Parceiros — Tipos Básicos** na aba de Compêndios de Itens.

O módulo exige o sistema **Tormenta20 1.6.0+** (verificado em 1.6.7) e Foundry VTT 13+.

## Como usar

1. Arraste o item do compêndio para a ficha do personagem (aba **Poderes** ou **Itens**).
2. Os efeitos com **transferência** entram sozinhos na aba **Efeitos** do ator e já alteram Defesa, ataques, dano, perícias, deslocamento etc.
3. Para os bônus condicionais (por exemplo, “+1d6 em uma rolagem de dano à distância, 1/rodada”):
   - abra a aba **Efeitos** do ator;
   - **ative** o efeito antes da rolagem;
   - faça a rolagem;
   - **desative** o efeito em seguida.
4. Quando o parceiro evoluir, **remova** o item antigo e adicione o novo. Assim os bônus não se acumulam por engano.

> **Progressão de parceiros:** no livro básico, iniciante, veterano e mestre são categorias alternativas. Quando o texto diz “muda para”, o benefício novo **substitui** o anterior. Quando diz “como acima”, os benefícios **acumulam**. Por isso cada versão é um item separado: remova a versão antiga ao adicionar a nova.

> **Montarias:** os bônus de deslocamento e de combate só valem enquanto o personagem estiver montado e conduzindo a montaria. Desative os efeitos do item se desmontar. As regras de montaria do Tormenta20 continuam valendo (Cavalgar, quedas etc.). Exceção: o **grifo iniciante** é um filhote, não pode ser montado e concede apenas o bônus de dano.

## Organização do compêndio

- **Parceiros — Tipos Básicos** (36 itens): os 12 tipos nas três versões.
- **Montarias — Tipos Básicos** (18 itens): as 6 montarias nas três versões.

## Parceiros

| Tipo | Iniciante | Veterano | Mestre | Automação |
|---|---|---|---|---|
| Combatente | +2 em ataques | +3 em ataques | +4 em ataques; 5 PM por ataque extra 1/rodada | Ataque automático; ataque extra manual |
| Guardião | +2 Defesa | +3 Defesa | +4 Defesa; +2 Fort/Ref/Vont | Automático |
| Fortão | +1d8 dano corpo a corpo 1/rodada | +1d12 | +3d6 | Condicional |
| Atirador | +1d6 dano à distância 1/rodada | +1d10 | +2d8 | Condicional |
| Perseguidor | +2 Percepção/Sobrevivência | Sentidos Aguçados | Percepção às Cegas | Iniciante automático; habilidades manuais |
| Vigilante | +2 Percepção/Iniciativa | Esquiva Sobrenatural | Olhos nas Costas | Iniciante automático; habilidades manuais |
| Ajudante | +2 em duas perícias | +2 em três perícias | +4 em três perícias | Manual (perícias definidas pelo parceiro; exceto Luta/Pontaria) |
| Adepto | −1 PM em magias de 1º círculo | também 2º círculo | cumulativo com outras reduções | Manual |
| Magivocador | +1 dado de dano de magia | +1 dado e +1 CD | +2 dados e +2 CD | Manual |
| Médico | 1 PM cura 1d8+1 | 3 PM cura 3d8+3 ou remove condição | 5 PM cura 6d8+6 | Manual |
| Destruidor | 1 PM causa 2d6 | 2 PM causa 4d6 | 4 PM causa 6d6 em área | Manual |
| Assassino | Ataque Furtivo +1d6 | +1d6 e flanquear (+2) | +2d6 e flanquear (+2) | Condicional |

## Montarias

| Montaria | Iniciante | Veterano | Mestre | Automação |
|---|---|---|---|---|
| Cavalo / pônei | 12m; ação de movimento extra | 15m; +2 ataques (posição elevada) | 15m; +2 ataques; segunda ação de movimento extra | Deslocamento e ataque automáticos; ações extras manuais |
| Cão de Caça | 9m; faro; ação de movimento extra | 12m; +2 Defesa; faro; ação extra | 12m; +2 Defesa; faro; derrubar 1/rodada | Deslocamento e Defesa automáticos; resto manual |
| Grifo | +1d8 dano 1/rodada; **não monta** | +1d8; voo 18m | +1d8; voo 18m; ação extra | Dano condicional; voo automático; ação extra manual |
| Trobo | 9m; ação extra; +1 resistências | 12m; ação extra; +2 resistências | 12m; ação extra; +5 resistências | Deslocamento e resistências automáticos; ação extra manual |
| Lobo-das-Cavernas / lobo comum | 12m; ação extra | 15m; +1d8 dano 1/rodada | 15m; +1d8; derrubar 1/rodada | Deslocamento automático; dano condicional; resto manual |
| Lobo-Crocodilo / gorlogg | 12m; +1d6 dano 1/rodada | 12m; +1d10 | 15m; +2d8 | Deslocamento automático; dano condicional |

## O que é automatizado

| Benefício | Efeito |
|---|---|
| Defesa | `system.attributes.defesa.bonus` |
| Ataque (geral, corpo a corpo, à distância) | `system.modificadores.ataque.*` |
| Dano (geral, corpo a corpo, à distância, magia) | `system.modificadores.dano.*` |
| Perícias | `system.pericias.<perícia>.bonus` |
| Resistências (Fortitude, Reflexos, Vontade) | `system.pericias.fort/refl/vont.bonus` |
| Deslocamento (terrestre/voo) | `system.attributes.movement.*.base` |

## O que NÃO é automatizado

Alguns benefícios não têm campo passivo no sistema e estão descritos no texto do item, para aplicação manual:

- redução de custo em PM (o campo de custo não aceita valores negativos);
- ações de movimento extras;
- ataque extra do Combatente mestre;
- curas e danos de habilidades ativadas (Médico, Destruidor);
- dados extras de dano de magia e bônus de CD do Magivocador;
- escolha das perícias do Ajudante (o parceiro define quais são; exceto Luta e Pontaria);
- habilidades concedidas: Sentidos Aguçados, Percepção às Cegas, Esquiva Sobrenatural, Olhos nas Costas, faro;
- manobra derrubar como ação livre (Cão de Caça mestre e Lobo-das-Cavernas mestre).

## Conteúdo

- **54 itens** em **2 pastas**.
- **51 efeitos**: 32 automáticos e 19 condicionais.
- Itens que dependem de escolha ou de habilidade sem campo passivo não têm efeito automático; o texto do item explica a aplicação manual.

## Créditos

Textos baseados em *Tormenta20 — Edição Jogo do Ano* (Jambô Editora). Não comercializar este módulo nem seu conteúdo.

---

Feito por **@xx_.luis._xx**.
