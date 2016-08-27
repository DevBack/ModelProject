# Introducão

Esse documento tem como finalidade desenvolver as políticas do projeto para controle de gerência e configuracão de software.

# Política de Branches
                                    R1                             R2
Master  |----------------------------|----------------------------- |

Dev        |-------------------------|----------------------------- |

uc1            |----------|      

uc2              |---------------|

uc2_Alan               |-----|

uc2_Hugo           |-----------|

Segundo o modelo apresentado de baixo para cima: cada desenvolvedor deve ter sua brach caso seja alocado para trabalhar em um caso de uso. Terminado o trabalho, o desenvolvedor deve submeter a branch ao sistema de integracão continúa. Caso todos testes tenham resultado positivo o desenvolvedor solicita a revisão da branch que estando em perfeito estado deve ser mergeda na branch principal do caso de uso. As branches de caso de uso devem ser integradas a branch dev após os resultados posivitos na integracão contínua. Por sua vez a branch deve somente será integrada a master na integra das releases.

