Inicializando Dart VM...

Dart VM pronta para uso.

Para entrar em contato, envie um email para guilhermecm1505@gmail.com.

C:\Users\guilherme> type main.dart

```dart
void main() {
  const cargo = 'Desenvolvedor Flutter';
  const foco = 'Aplicações Mobile';

  final eu = InformacoesPessoais(
    nome: 'Guilherme Carvalho',
    cargo: cargo,
    foco: foco,

    contato: Contato(
      email: Uri.parse('mailto:guilhermecm1505@gmail.com'),
      linkedin: Uri.https('www.linkedin.com', 'in/guilherme-carvalho-mobdev'),
      github: Uri.https('github.com', 'guilhermecarv32'),
    ),

    flutter: FlutterInfo(
      anosExperiencia: '2+',
      possuiAppsPublicados: true,
      qtdApps: '20+', // E contando...
      principaisRecursos: <String>[
        'Integração com APIs REST',
        'Autenticação',
        'Consumo de dados em tempo real',
        'Interfaces limpas e responsivas',
      ],
    ),

    backend: BackendInfo(
      stacks: <String>[
        'Node.js',
        'FastAPI',
        'Spring Boot',
        'PHP',
      ],
      atuacao: <String>[
        'Construção de APIs REST',
        'Automações com Python',
        'Processamento de dados',
        'Integrações com serviços externos',
      ],
    ),

    // Outras habilidades relevantes
    outrasHabilidades: <String>[
      'React',
      'PostgreSQL',
      'Firebase',
      'UI / UX',
      'HTML / CSS',
    ],

    projetos_relevantes: <Projeto>[
      Projeto(
        'XPlearn',
        descricao: 'Plataforma gamificada de estudos',
        stack: ['FastAPI', 'Quasar'],
        url: Uri.https('github.com', 'SEU_USERNAME/xplearn'),
      ),
      Projeto(
        'Dança+',
        descricao: 'Aplicativo gamificado com foco no engajamento de alunos',
        stack: ['Flutter', 'Firebase'],
        url: Uri.https('github.com', 'SEU_USERNAME/danca-mais'),
      ),
      Projeto(
        'Dani e Ellas',
        descricao: 'Sistema de loja usado em negócio real',
        stack: ['Electron', 'Firebase'],
        url: Uri.https('github.com', 'SEU_USERNAME/dani-e-ellas'),
      ),
      Projeto(
        'Expenses App',
        descricao: 'App mobile de controle financeiro',
        stack: ['Flutter'],
        url: Uri.https('github.com', 'SEU_USERNAME/expenses-app'),
      ),
    ],

    status: Status(
      aprendendo: true,
      abertoParaOportunidades: true,
      construindo: 'Soluções reais para problemas reais',
    ),
  );

  print(eu);
}

C:\Users\guilherme> dart run main.dart

✔ Nome: Guilherme Carvalho
✔ Cargo: Desenvolvedor Flutter
✔ Foco: Aplicações Mobile

📱 Flutter:
- Experiência: 2+ anos
- Apps publicados: sim
- Quantidade: 20+

⚙️ Backend:
- Node.js, FastAPI, Spring Boot, PHP

🧠 Outras habilidades:
- React, PostgreSQL, Firebase, UI/UX, HTML/CSS

🚀 Status:
- Aprendendo: sim
- Aberto para oportunidades: sim
- Construindo: Soluções reais para problemas reais

✨ Execução finalizada com sucesso.
