# Super Bomberman 5 Gold PT-BR — v131 (MÁQUINA)

**Status: versão experimental — teste visual no emulador pendente.**

## Alterações documentadas
- Baseada na v130.
- Restaura **MÁQUINA** no menu REGRAS, recuperando o registro gráfico da v127.
- Preserva a alteração do Teste de Som da v130, conforme o checkpoint.

## Aplicação
1. Utilize sua própria cópia legal da ROM japonesa **Super Bomberman 5 Gold Cartridge**.
2. Confirme que a ROM limpa possui CRC32 **4590AE9D** (conforme a documentação do checkpoint).
3. Faça backup e aplique o IPS em uma cópia limpa com um aplicador de IPS.
4. Verifique o resultado no emulador.

## Integridade
- Patch IPS SHA-256: `29a09cb2ea7529044a01501dc1401f76207c3d588e99f222219eb395fd9bbede`
- ROM final de referência CRC32: `051E92CA`
- ROM final de referência SHA-256: `ca65acb39ce4a929f4fd52b4043a73d6584163cecbb23c0b2fe9493113b65ee7`
- Registros IPS sintaticamente analisados: 133.

## Limitações
A sintaxe IPS e o CRC32 da ROM incluída no checkpoint foram verificados. **Não foi comprovado neste preparo que o patch reproduz a ROM final a partir da base original**, pois a ROM japonesa limpa não foi fornecida nesta etapa. Também não houve teste de emulação.

**Não inclua a ROM modificada nem a ROM original no repositório público.**
