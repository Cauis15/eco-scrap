# eco-scrap
Site para apresentação de projeto da matéria Projeto integrador do curso  de Desenvolvimento de sistemas do ETE Porto Digital

EcoScrap — Reciclagem de E-lixo (HTML & CSS Puro)

Protótipo de aplicação web desenvolvido para incentivar o descarte correto de lixo eletrônico (e-lixo) por meio de um sistema de recompensas com **Moedas de Carbono**. Projeto desenvolvido para o curso técnico em Desenvolvimento de Sistemas, explorando recursos avançados de CSS para interatividade sem o uso de JavaScript.

Funcionalidades
- **Navegação por Abas sem JS:** Alternância entre as telas (*Cadastro*, *Pontos de Coleta*, *Minhas Moedas* e *Trocar Moedas*) utilizando `<input type="radio">` e o seletor `:checked` do CSS.
- **Cadastro Simulado:** Formulário com seleção de perfil (*Usuário Comum*, *Empresa* ou *Parceiro*) e exibição de feedback visual de aprovação controlado via CSS.
- **Pontos de Coleta Interativos:** Listagem de ecopontos com endereços, horários e rotas expansíveis criadas com as tags nativas `<details>` e `<summary>`.
- **Carteira de Moedas:** Exibição do saldo atual de Moedas de Carbono e tabela com o histórico de descartes realizados.
- **Resgate de Recompensas:** Catálogo de prêmios (cupom de desconto, ecobag e fone de ouvido) com confirmação visual instantânea ao clicar.

Tecnologias e Técnicas Utilizadas
- **HTML5:** Estruturação semântica, formulários, tabelas e componentes nativos de acordeão (`<details>` / `<summary>`).
- **CSS3:** Layout responsivo com Flexbox, estilização de estado com `:checked`, seletor irmão geral (`~`) para controle de visibilidade e paleta temática sustentável.
