# CLR
> Common Language Runtime

## Situação Hipotética:
Imagine que você está em um congresso falando português, e há pessoas que falam várias outras línguas. Você pode:
* Falar em Inglês
* Falar em Alemão
* Falar em Dinamarquês

Supondo que haja tradutores para essas línguas, o CLR funciona como um tradutor para dispositivos em suas necessidades específicas.

### CLR e JIT
O CLR é comparável à JVM ou máquina virtual. O JIT (Just-In-Time) é um componente essencial do CLR, compilando o código intermediário (IL no .NET ou bytecode no Java) em código nativo executável pelo processador.

#### Como Funciona o JIT:
- **Compilação Antecipada (AOT)**: Código compilado antes da execução.
- **Just-In-Time (JIT)**: Código compilado durante a execução conforme necessário.

#### Vantagens do JIT:
- **Otimização em Tempo de Execução**: Otimiza o código baseado no comportamento real do programa.
- **Portabilidade**: Código intermediário pode ser executado em qualquer plataforma com um JIT adequado.

#### Desvantagens do JIT:
- **Tempo de Inicialização**: Pode haver atraso inicial devido à compilação JIT.
- **Consumo de Recursos**: Compilação JIT consome CPU e memória durante a execução.
