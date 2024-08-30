# SEGURANÇA

## cascata de verificações
LE = leitura & ES = escrita

1. login
   * Tecnicos
   * Base
   * ADM
3. LE ordens de serviços
   * Base
   * ADM
4. LE/ES ordens de serviços
   * Base
   * ADM
5. LE a dados de clientes e tecnicos
   * ADM
   * Base
6. LE/ES dados de clientes e tecnicos
   * ADM
