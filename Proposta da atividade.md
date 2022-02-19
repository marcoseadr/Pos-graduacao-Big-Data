
# Texto
Para realização da atividade, optei a Bíblia para análisar se a lei de Zipf se aplica em textos religiosos. Por ser um Livro extenso, palavras que têm menos de 3.000 menções não aparecem no gráfico, confirmando a lei de Zipf, liderando a lista a palavra "e" com 37.921 mensões, destaca-se as menções das palavras "Senhor" na 10º posição e "Deus" na 19º posição, em meio artigos e preposições.

# Atividade
A frequência de termos (quantidade que cada palavra aparece em um texto) tem grande importância em uma série de problemas envolvendo busca, classificação e sumarização automática de documentos. 

A ideia é que as palavras que as frequências das palavras que um texto contém pode dar uma boa pista do conteúdo do texto.  

Hans Peter Luhn (1957): The weight of a term that occurs in a document is simply proportional to the term frequency. 

Entretanto, parece haver termos muito frequentes, como artigos, preposições etc. que parecem contribuir muito pouco para explicar o conteúdo de um texto. 

George Kingsley Zipf: Zipf's law states that given a large sample of words used, the frequency of any word is inversely proportional to its rank in the frequency table. So word number n has a frequency proportional to 1/n. 

Essa é uma lei geral que que ocorre em todo o texto de produção humana e, importante, em qualquer língua. Esse princípio pode ser então empregado desde para decifrar códigos e texto em línguas antigas, como em modernos sistemas de mineração de texto (search engines, bibliotecas digitais, classificação automática de conteúdo etc.). Você pode acessar:  

https://demonstrations.wolfram.com/ZipfsLawAppliedToWordAndLetterFrequencies/ 

para uma demonstração disso. 



Tarefa 

Implemente um programa em Python (Python notebook) que constrói um dicionário de termos de um documento (mínimo 1000 palavras) com a frequência de cada termo permitindo confirmar a lei de Zipf para o documento selecionado.  
