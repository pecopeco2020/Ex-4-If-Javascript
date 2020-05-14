# Ex-4-If-Javascript
Escreva uma função que dado um total de anos de estudo retorna o quão experiente o usuário é

<html>
    <head></head>
    <body>
        <script>
            function experiencia(anos){
                var anos;
                if(anos>=0 && anos<1){
                    console.log("Iniciante");
                }
                    else if(anos>=1 && anos<3){
                        console.log("Intermediario");
                    }
                        else if(anos>=3 && anos<=6){
                            console.log("Avancado");
                        }
                            else if(anos>=7){
                                console.log("Jedi Master");
                            }
            }

            var anosEstudo = 0.3;
            experiencia(anosEstudo);
            //0-1 ano = iniciante
            //1-3 anos = intermediario
            //3-6 anos = avancado
            //7 acima = jedi master

        </script>
    </body>
</html>
