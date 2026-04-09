# O que foi difícil 

A maior dificuldade que eu encontrei durante esse exercício foi entender de verdade como funciona o fluxo de trabalho com várias branches e como elas se integram ao repositório principal. No começo, eu ficava meio perdida, sem saber exatamente em que momento as alterações de uma branch entravam na main. Foi aí que percebi que o Pull Request não é só um passo burocrático, mas sim uma etapa de revisão importante, e que o merge só acontece depois que alguém confirma manualmente no GitHub. Esse detalhe me obrigou a prestar muito mais atenção e foi um aprendizado que realmente fez diferença.

Outra coisa que me deu um baita nó na cabeça foi lidar com os conflitos de merge. Quando aparecem aquelas marcações no arquivo, confesso que bateu uma insegurança sobre qual parte do código deveria permanecer. Tive que parar e analisar cada trecho com calma, pra não acabar apagando nada importante sem querer. Além disso, me adaptar ao terminal, no meu caso o PowerShell, também foi um desafio. Qualquer erro de sintaxe ou caminho de diretório errado gerava mensagens de erro que eu ainda não conseguia interpretar na hora, então o processo inicial acabou sendo mais devagar do que eu imaginava. 

# O que ficou claro 

Apesar de tudo isso, algumas coisas começaram a fazer muito mais sentido. Agora consigo enxergar o ciclo do Git de forma lógica: criar uma branch, fazer modificações, usar git add, git commit e git push, tudo seguindo uma sequência que protege o projeto. Entendi que essa estrutura existe justamente para que novas funcionalidades possam ser testadas sem atrapalhar o que já está funcionando na branch principal.

Outro ponto que ficou bem claro pra mim foi a importância dos commits semânticos. No início, aqueles prefixos tipo feat:, fix: ou docs: pareciam só regras extras, mas agora vejo que eles deixam o histórico do projeto muito mais organizado e profissional. Isso facilita demais a hora de entender quando e por que uma mudança foi feita, algo que é essencial para qualquer desenvolvedor, mesmo iniciante. 

# O que ainda é confuso 

Mesmo assim, algumas coisas ainda me deixam meio insegura. Projetos grandes, onde várias pessoas mexem no mesmo arquivo ao mesmo tempo, ainda parecem complicados de coordenar. Resolver múltiplos conflitos simultaneamente ainda me parece um desafio e tanto. Além disso, alguns detalhes internos do Git, como o funcionamento do ponteiro HEAD e a recuperação de arquivos em estados específicos do histórico, ainda não estão totalmente claros pra mim. Sei que consigo lidar com o básico e que já entendi o fluxo individual, mas sei que dominar o uso avançado do Git vai depender de prática constante e da experiência em projetos de equipe nas próximas semanas.

No fim, percebo que, mesmo com essas dificuldades, estou aprendendo o básico do Git e que, com o tempo e prática ao longo do projeto, vou me acostumar de verdade com todo esse fluxo. Resolver conflitos, lidar com branches e entender os comandos vai ficando mais natural, e aos poucos eu vou me sentindo mais segura para trabalhar em equipe e acompanhar como um projeto real funciona sem ficar perdido.
