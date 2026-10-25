
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Basic Chemistry</title>

    <style>
        body {
            background-color:#0A192F;
            color:#FFFFFF;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        h1, h2 {
            color: #FFFFFF;
        }

        button {
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            margin: 5px;
        }

        .botao-quimica {
            background-color: blue;
            color: white;
        }

        .botao-info {
            background-color: green;
            color: white;
        }

        .botao-quimica:hover {
            background-color: darkblue;
        }

        .botao-info:hover {
            background-color: darkgreen;
        }

        #conteudo, #informacoes {
            margin-top: 20px;
        }

        .topico {
            margin-bottom: 25px;
        }

        .escondido {
            display: none;
        }
    </style>
</head>

<body>

    <h1>Basic Chemistry</h1>

    <h2>Bem-vindo ao Basic Chemistry!</h2>
    <p>Vamos aprender?</p>
    <p>Este site tem a finalidade de 
      auxiliar o aluno ou Docente no estudo basico da Química
      e ajudar o aluno a desenvolver conhecimentos e aplicar diariamente.</p>
    <button class="botao-quimica"
        onclick="mostrarQuimica()">QUÍMICA</button>

    <button class="botao-info"
        onclick="mostrarInfo()">Info</button>

    <div id="conteudo" class="escondido">

        <h2>Base da Química Geral</h2>

        <section class="topico">
            <h3>1. MATÉRIA</h3>
            <p>Matéria é tudo que tem massa e ocupa espaço.
            Os estados mais comuns são sólido, líquido e gasoso.
            Substância pura tem composição definida, como a água
            destilada (H₂O). Mistura contém várias substâncias,
            como a água do mar.</p>
        </section>

        <section class="topico">
            <h3>2. ÁTOMO</h3>
            <p>O átomo tem um núcleo com protões positivos e,
            geralmente, neutrões sem carga. Os eletrões têm carga
            negativa e ocupam regiões ao redor do núcleo.
            O número atómico (Z) é o número de protões.
            O número de massa (A) é a soma de protões e neutrões.
            Isótopos têm o mesmo número de protões e diferentes
            números de neutrões.</p>
        </section>

        <section class="topico">
            <h3>3. TABELA PERIÓDICA</h3>
            <p>A tabela periódica contém 118 elementos organizados
            por número atómico crescente. Os metais encontram-se
            sobretudo à esquerda e ao centro, e muitos ametais
            à direita. Os gases nobres estão no grupo 18.
            A regra do octeto é uma regra útil para compreender
            muitas ligações químicas, mas tem exceções.</p>
            <p>Famílias importantes: grupo 1, metais alcalinos;
            grupo 2, alcalino-terrosos; grupo 17, halogénios;
            grupo 18, gases nobres.</p>
        </section>

        <section class="topico">
            <h3>4. LIGAÇÕES QUÍMICAS</h3>
            <p>Iónica: há transferência de eletrões e atração
            entre iões, como no NaCl.
            Covalente: os átomos partilham eletrões, como em
            H₂O, O₂ e CO₂.
            Metálica: os eletrões deslocalizados ajudam a explicar
            a condução elétrica dos metais, como Fe, Au e Cu.</p>
        </section>

        <section class="topico">
            <h3>5. REAÇÕES QUÍMICAS</h3>
            <p>Os reagentes transformam-se em produtos.</p>
            <p>Síntese: 2H₂ + O₂ → 2H₂O</p>
            <p>Decomposição: 2H₂O → 2H₂ + O₂</p>
            <p>Simples troca: Zn + 2HCl → ZnCl₂ + H₂</p>
            <p>Dupla troca: NaCl + AgNO₃ → AgCl + NaNO₃</p>
            <p>Lei de Lavoisier: num sistema fechado, a massa
            total dos reagentes é igual à massa total dos produtos.</p>
        </section>

        <section class="topico">
            <h3>6. CÁLCULOS QUÍMICOS</h3>
            <p>Quantidade de matéria: n = m / M.
            m é a massa em gramas e M é a massa molar em g/mol.
            Um mol contém aproximadamente 6,022 × 10²³ entidades.</p>
            <p>Concentração molar: C = n / V, com V em litros.</p>
            <p>Densidade: d = m / V.</p>
            <p>Exemplo: 36 g de água correspondem a
            n = 36 / 18 = 2 mol.</p>
        </section>

        <section class="topico">
            <h3>7. ÁCIDOS, BASES E pH</h3>
            <p>Em água, um ácido pode aumentar a concentração de H₃O⁺.
            Uma base pode aumentar a concentração de OH⁻.
            A 25 °C, uma solução aquosa neutra tem pH 7.
            Valores abaixo de 7 são ácidos e acima de 7 são básicos.</p>
            <p>Neutralização: HCl + NaOH → NaCl + H₂O.</p>
        </section>

        <section class="topico">
            <h3>8. SOLUÇÕES E GASES</h3>
            <p>Solução é uma mistura homogénea de soluto e solvente,
            como sal dissolvido em água.</p>
            <p>Gás ideal: PV = nRT.
            P é pressão, V é volume, n é quantidade de matéria,
            R é a constante dos gases e T é a temperatura em kelvin.</p>
            <p>Conversão: T(K) = T(°C) + 273,15.</p>
        </section>

        <section class="topico">
            <h3>9. OXIDAÇÃO E REDUÇÃO (REDOX)</h3>
            <p>Oxidação é perda de eletrões; redução é ganho
            de eletrões. A oxidação aumenta o número de oxidação,
            enquanto a redução o diminui.
            O agente redutor sofre oxidação e o agente oxidante
            sofre redução. Pilhas e baterias utilizam reações redox.</p>
        </section>

        <section class="topico">
            <h3>10. EQUILÍBRIO QUÍMICO</h3>
            <p>Em certas reações reversíveis, a velocidade da reação
            direta torna-se igual à da reação inversa.
            O equilíbrio é dinâmico: as reações continuam a ocorrer.</p>
            <p>Princípio de Le Chatelier: quando as condições mudam,
            o sistema tende a contrariar essa alteração.
            O efeito da temperatura depende de a reação ser
            endotérmica ou exotérmica.</p>
            <p>N₂ + 3H₂ ⇌ 2NH₃</p>
        </section>

        <section class="topico">
            <h3>11. TERMOQUÍMICA</h3>
            <p>Reações exotérmicas libertam calor e têm ΔH negativo.
            Reações endotérmicas absorvem calor e têm ΔH positivo.</p>
            <p>ΔH = H dos produtos − H dos reagentes.</p>
        </section>

        <section class="topico">
            <h3>12. CINÉTICA QUÍMICA</h3>
            <p>A cinética estuda a velocidade das reações.
            Temperatura, concentração, superfície de contacto
            e catalisadores podem influenciar essa velocidade.
            Um catalisador acelera a reação sem ser consumido
            globalmente.</p>
        </section>

        <section class="topico">
            <h3>13. FUNÇÕES ORGÂNICAS</h3>
            <p>A Química Orgânica estuda principalmente os compostos
            de carbono. Exemplos de funções:
            álcoois (–OH), ácidos carboxílicos (–COOH),
            aldeídos, cetonas e aminas.
            O carbono forma geralmente quatro ligações.</p>
        </section>

        <section class="topico">
            <h3>14. ELETROQUÍMICA</h3>
            <p>Uma pilha transforma energia química em elétrica
            através de uma reação espontânea.
            A eletrólise utiliza energia elétrica para provocar
            uma reação não espontânea, sendo usada, por exemplo,
            no revestimento de metais.</p>
        </section>

        <section class="topico">
            <h3>15. LEIS DOS GASES</h3>
            <p>Lei de Boyle, a temperatura constante:
            P₁V₁ = P₂V₂.</p>
            <p>Lei de Charles, à pressão constante:
            V₁/T₁ = V₂/T₂.</p>
            <p>Lei geral dos gases, para a mesma quantidade de gás:
            P₁V₁/T₁ = P₂V₂/T₂.</p>
            <p>As temperaturas devem estar em kelvin.</p>
        </section>

        <section class="topico">
            <h3>16. DICAS PARA A PROVA</h3>
            <p>Balanceia as equações químicas.
            Confirma as unidades e converte a temperatura para kelvin
            quando necessário.
            Nos cálculos, identifica os dados e escolhe a fórmula
            adequada antes de substituir os valores.</p>
        </section>

        <section class="topico">
            <h3>17. ISOMERIA</h3>
            <p>Isómeros têm a mesma fórmula molecular, mas diferem
            na estrutura ou na disposição espacial.
            Por exemplo, C₂H₆O pode representar etanol
            (CH₃CH₂OH) ou éter dimetílico (CH₃OCH₃).
            Existem isomerias estruturais e estereoisomerias,
            incluindo cis-trans e isomeria óptica.</p>
        </section>

        <section class="topico">
            <h3>18. POLÍMEROS</h3>
            <p>Polímeros são moléculas grandes constituídas por
            unidades repetidas. Existem polímeros naturais,
            como proteínas, amido e borracha natural, e sintéticos,
            como polietileno, PVC, PET e nylon.
            A degradação dos plásticos depende do material
            e das condições ambientais.</p>
        </section>

        <section class="topico">
            <h3>19. RADIOATIVIDADE</h3>
            <p>Alguns núcleos atómicos instáveis emitem radiação.
            A radiação alfa tem baixo poder de penetração;
            a beta tem penetração intermédia; a gama é muito
            penetrante e requer proteção adequada.
            Meia-vida é o tempo necessário para que metade
            dos núcleos radioativos de uma amostra decaia.
            A radioatividade tem aplicações médicas e energéticas.</p>
        </section>

        <section class="topico">
            <h3>20. FUNÇÕES INORGÂNICAS</h3>
            <p>As principais classes estudadas incluem ácidos,
            bases, sais e óxidos.
            Exemplos: NaCl é um sal; CO₂ é um óxido;
            CaO é óxido de cálcio.
            CaO + H₂O → Ca(OH)₂.
            CO₂ + H₂O ⇌ H₂CO₃.</p>
        </section>

        <section class="topico">
            <h3>21. SOLUBILIDADE E FORÇAS INTERMOLECULARES</h3>
            <p>A solubilidade depende das interações entre
            soluto e solvente. A regra “semelhante dissolve
            semelhante” é uma orientação útil.
            As forças intermoleculares incluem forças de London,
            interações dipolo-dipolo e ligações de hidrogénio.
            Estas influenciam propriedades como a temperatura
            de ebulição.</p>
        </section>

        <section class="topico">
            <h3>22. pH E SOLUÇÕES TAMPÃO</h3>
            <p>O sangue saudável tem normalmente pH próximo de 7,4.
            Sistemas tampão ajudam a resistir a alterações de pH.
            Um exemplo importante é o sistema
            H₂CO₃ / HCO₃⁻.</p>
            <p>Para soluções aquosas diluídas, em condições
            adequadas: pH = −log[H₃O⁺].
            A 25 °C, pH + pOH = 14.</p>
            
              <h2>From Petro MM energies</h2>
        </section>

    </div>

    <div id="informacoes" class="escondido">
        <h2>Informações da aplicação</h2>
        <p><strong>Nome do site:</strong> Basic Chemistry</p>
        <p><strong>Criador:</strong> Fábio Alberto Mussengue Martins</p>
        <p><strong>Versão:</strong> 1.0</p>
        <p><strong>Aplicação de criação:</strong> Acode</p>
        <p><strong>Equipa técnica:</strong> Rúben Martins</p>
        <p><strong>Objetivo:</strong> Auxiliar alunos e docentes
        a compreender a Química de forma simples.</p>

      <h2>From Petro MM energies</h2>
    </div>

    <script>
        function mostrarQuimica() {
            document.getElementById("conteudo").classList.remove("escondido");
            document.getElementById("informacoes").classList.add("escondido");
        }

        function mostrarInfo() {
            document.getElementById("informacoes").classList.remove("escondido");
            document.getElementById("conteudo").classList.add("escondido");
        }
    </script>

</body>
</html>
