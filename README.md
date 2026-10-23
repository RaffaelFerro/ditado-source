# Ditado

<img src="icon.png" width="96" alt="Ícone do Ditado">

Ditado por voz para iPhone (e Mac) em português do Brasil. Você fala do seu jeito e o texto entra
arrumado onde está o cursor, em qualquer app.

## Instalar no iPhone

Adicione este source na sua loja de sideload (AltStore, SideStore, Feather e afins):

```
https://raw.githubusercontent.com/RaffaelFerro/ditado-source/main/source.json
```

Ou baixe o `Ditado.ipa` em [Releases](https://github.com/RaffaelFerro/ditado-source/releases) e instale com a
sua ferramenta de sideload. O IPA vem sem assinatura; a ferramenta assina com a sua conta (com conta grátis,
renove a cada 7 dias). Traz 2 extensões (teclado e widgets).

Requer **iOS 26**.

## Primeiro uso

1. Abra o **Ditado** e cole uma chave do **Groq** ([grátis em console.groq.com/keys](https://console.groq.com/keys)). Sem chave, o texto sai só limpo, sem arrumação.
2. Toque em **Liberar o microfone**.
3. **Ajustes › Geral › Teclado › Teclados › Adicionar Novo Teclado › Ditado**, depois toque em **Ditado** e ligue **Permitir Acesso Total** (é o que deixa o teclado falar com o app).
4. Para ligar o microfone sem abrir o app: **Ajustes › Acessibilidade › Toque › Toque nas Costas › Toque Duplo › "Ligar o Ditado"**, ou adicione o controle **Ditado** na Central de Controle. Aceite as **Atividades ao Vivo**.

## Usar

Troque para o teclado **Ditado** (🌐), escolha o nível, toque no microfone e fale; o rascunho aparece ao vivo.
Toque em **Parar** e ele vira o texto arrumado.

- **1 Fiel**: tudo que você falou, só sem "ééé", "tipo", "né" e com as autocorreções ("sexta, não, quinta" → quinta).
- **2 Arrumado**: as mesmas ideias em frases claras.
- **3 Editor**: organiza as ideias, em tópicos quando ajuda.

## Mac

Em [Releases](https://github.com/RaffaelFerro/ditado-source/releases) também tem o `Ditado-Mac.zip` (macOS 26):
fica na barra de menus, **segure fn** para ditar. Na primeira abertura o macOS pode bloquear: clique com o botão
direito › Abrir, ou Ajustes do Sistema › Privacidade e Segurança › Abrir Mesmo Assim. Libere Microfone,
Acessibilidade e Monitoramento de Entrada.

## Privacidade

A transcrição é feita pela Apple no próprio aparelho. Para arrumar o texto, a fala transcrita (e um pouco do texto
ao redor do cursor) vai para o Groq com a **sua** chave. Nada passa por servidor do Ditado; a chave fica no Chaveiro.

© 2026 Raffael Ferro. Todos os direitos reservados.
