# Features Module

Esta pasta contém os módulos de funcionalidades da aplicação. Cada feature deve ser um módulo independente.

## Estrutura

Cada feature deve seguir a seguinte estrutura:
```
feature-name/
├── components/     # Componentes específicos da feature
├── services/       # Serviços específicos da feature
├── models/         # Interfaces e tipos específicos
└── feature.routes.ts  # Rotas da feature
```

## Uso

Cada feature deve ser lazy loaded e conter apenas o necessário para sua funcionalidade. 