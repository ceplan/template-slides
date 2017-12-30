# PowerPoint template

Este modelo (template) de apresentação de slides foi desenvolvido para o Centro de Educação do Planalto Norte (CEPLAN) utilizando PowerPoint. O template foi derivado do modelo [modelo padrão da UDESC](http://www.udesc.br/arquivos/udesc/id_cpmenu/5524/template_TEMPLATE_DE_APRESENTA__O_UDESC_15_09_16_15029104943981_5524.pptx)

## Dependências:

- PowerPoint: versão > 2013

## Como utilizar:
- A pasta **fonts** contém as fontes utilizadas no template. Favor instalar essas fontes antes de prosseguir.
- O arquivo *sample.pptm* contém um exemplo do uso do template utilizando macros.
- Para criar uma nova apresentação utilize o arquivo *template.potm*.
- Utilize as opções de layout dos slides disponíveis no template.
- Para adicionar ou remover a barra de progresso nos slides habilite macros (veja como fazer [aqui](https://support.office.com/pt-br/article/Habilitar-ou-desabilitar-macros-em-arquivos-do-Office-12b036fd-d140-4e74-b45e-16fed1a7e5c6) e a aba do modo desenvolvedor.

### Como habilitar o modo desenvolvedor e adicionar a barra de progresso:
- Vá em *Arquivo* > *Opções* > *Personalizar Faixa de Opções*.
- No lado direito (Guias Principais) procure por *Desenvolvedor* e marque a caixa de seleção.
- Clique em *OK*.
- Pronto, agora aparecerá uma aba *Desenvolvedor* ao lado da aba *Exibir*. Clique nessa aba.
- Clique em *Macros*. Abrirá uma janela mostrando as macros disponíveis para utilização. 
- Para adicionar a barra de progresso clique em *AddProgressBar* e então no botão *Executar*. 
	- Observações:
		- Faça o procedimento ao finalizar a sua apresentação para adicionar em todas os slides.
		- A barra não é adicionada automaticamente a cada novo slide inserido.
		- No último slide não é inserido a barra de progresso, pois é considerado como slide de **Obrigado**.
		- Caso deseje alterar o comportamento o código se encontra em *Visual Basic* na aba *Desenvolvedor*.
- Para adicionar a barra de progresso clique em *RemoveProgressBar* e então no botão *Executar*.

## Dúvidas ou melhorias?
- Crie uma **issue** para dúvidas, bugs ou sugestões de melhorias.
- Realize um **pull request** se você realizou alguma melhoria.
