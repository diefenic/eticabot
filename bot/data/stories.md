## story_brindes
* brindes
    - utter_brindes
    - utter_continuar_conversa

## story_codigo_etica
* codigo_etica
    - utter_codigo_etica
    - utter_continuar_conversa

## story_competencias_atribuicoes
* competencia_atribuicoes
    - utter_competencias_atribuicoes
    - utter_continuar_conversa

## story_composicao
* composicao
    - utter_composicao
    - utter_continuar_conversa

## story_login_form
* request_login
  - utter_login_form
  - login_form
  - form{"name": "login_form"}
  - form{"name": null}
* afirmar
  - utter_finaliza_forms

## story_login_form
* request_login
  - utter_login_form
  - login_form
  - form{"name": "login_form"}
* cancelar
  - utter_pergunta_cancelar
* negar
  - form{"name": "login_form"}
  - form{"name": null}
  - utter_finaliza_forms

## story_login_form_cancelar
* request_login
  - utter_login_form
  - login_form
  - form{"name": "login_form"}
* cancelar
  - utter_pergunta_cancelar
* afirmar
  - action_deactivate_form
  - form{"name": null}
  - utter_forms_cancelado
  - utter_continuar_conversa
* negar
  - utter_despedir

## story_login_form_cancelar
* request_login
  - utter_login_form
  - login_form
  - form{"name": "login_form"}
* cancelar
  - utter_pergunta_cancelar
* afirmar
  - action_deactivate_form
  - form{"name": null}
  - utter_forms_cancelado
  - utter_continuar_conversa

## testa acoes
* cumprimentar
    - utter_cumprimentar
* testa_acoes
    - action_teste

## testa acoes
* testa_acoes
    - action_teste

## testa slots
* informa_telefone
    - action_telefone

## path_license 1
* license
    - utter_license  
    - utter_continuar_conversa


## path_license 2
* cumprimentar
    - utter_cumprimentar
* license
    - utter_license
    - utter_continuar_conversa

## path_como_estou 1
* como_estou
    - utter_como_estou
    - utter_continuar_conversa

## path_como_estou 2
* cumprimentar
    - utter_cumprimentar
* como_estou
    - utter_como_estou
    - utter_continuar_conversa

## cumprimentar
* cumprimentar
    - utter_cumprimentar

## Despedir
* despedir
    - utter_despedir

## Tudo Bem Story
* tudo_bem
    - utter_tudo_bem

## Oi Tudo Bem Story 
* cumprimentar
    - utter_cumprimentar
* tudo_bem
    - utter_tudo_bem

## Nao entendi
* diga_mais
    - utter_diga_mais  

## fallback
* out_of_scope
    - utter_fallback

## negar sem contexto
* negar
    - utter_despedir

## elogios 1
* elogios
    - utter_elogios
    - utter_continuar_conversa

## elogios 2
* cumprimentar
    - utter_cumprimentar
* elogios
    - utter_elogios
    - utter_continuar_conversa

## meajuda 1
* o_que_sei_falar
    - utter_o_que_sei_falar

## meajuda 2
* cumprimentar
    - utter_cumprimentar
* o_que_sei_falar
    - utter_o_que_sei_falar

## objetivo
* objetivo
    - utter_objetivo

## story_limpar_slots
* limpar_slots
    - action_restart

