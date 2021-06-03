# (Audio Visualizer)



## (Instalare)
Open in Max MSP / Ableton Max 4 Live

## (Utilizare)

Drag & Drop la Soundfile si play.

## (Istoric)

(13.05) Research

(3.06) Implementare Functionalitatii de Baza

(X.06) Adaugarea unor elemente si functionalitati extra cum ar fi, pozitionarea
corecta a 'visualizerului' cand se deschide patchul dar si colorarea lui, deoarece
in acest moment cand se deschide, acesta o face cu culorile default
(backgroundul fiind negru deoarece asa este setat din obiectul jit.world
@erase color 0.0.0.1 care este negru insa nu m-am hotarat ce culoare v a avea
acesta).

## (Link-uri)

Fisiere: Patchul + Piesa Demo cu care am testat funct.
https://we.tl/t-1Q5NEtsKeu

https://docs.cycling74.com/max7/tutorials/jitindex

https://docs.cycling74.com/max8/vignettes/working_with_video_in_jitter_topic
^Linkul care m-a ajutat cel mai mult.

https://docs.cycling74.com/max8/tutorials/07-Generating%20Geometry

https://docs.cycling74.com/max8/tutorials/08-Audio%20into%20a%20matrix




# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.

   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.
