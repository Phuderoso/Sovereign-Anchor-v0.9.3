# Sovereign Anchor - Arquitetura Detalhada v0.9.3

## Fluxo de Ativação

1. Lemon-Venom (Assembly) → Stage 0
2. Verificação 0x534F4C56
3. Load Sovereign Core LKM
4. Ativação de ftrace hooks + DKOM
5. Injeção do RingReaper io_uring agent
6. Sisters entram em modo de auto-cura

## Objetivo
Persistência resiliente contra LKRG, eBPF, Falco, Elastic EDR e kernel integrity checks.

## Próximos Passos
- Implementação completa do bootstrap Lemon-Venom
- Integração com RingReaper
- Desenvolvimento das Sisters em SHM

