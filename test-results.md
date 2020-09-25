#Systeem informatie

-   OS: Manjaro Linux v5.19.5 (Plasma KDE)
-   IDE: Visual Studio code
-   NodeJS v14.11.0

#Tests

-   Ik liep aan tegen de fout:

Error: ENOSPC: System limit for number of file watchers reached, watch '/home/jeroen/OneDrive/Indicium/Git-Repos/Hacktoberfest01/hacktoberfest-fest-2020-2/client/public'

Deze heb ik opgelost door: echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p

-   Nog een fout was dat hij de module niet kan vinden
    ERROR Failed to compile with 1 errors 11:17:57 AM

This relative module was not found:
../../modules/vue-example in ./node_modules/cache-loader/dist/cjs.js??ref--12-0!./node_modules/babel-loader/lib!./node_modules/cache-loader/dist/cjs.js??ref--0-0!./node_modules/vue-loader/lib??vue-loader-options!./src/App.vue?vue&type=script&lang=js&

Deze is opgelost door in de modules npm run build uit te voeren in de modules

-   Opzetten ging eigenlijk wel goed, liep maar tegen 2 fouten aan maar misschien komt dat omdat ik NodeJS en al eens een VueJS project heb opgezet

-   Hoe koppelen we de databases aan elkaar dat iedereen vergelijkebare data heeft?
-   Welke gegevens slaan we op en welke niet (Kan tijdens overleg)
-   Modules misschien wat kort uitgelegd denk wat meer over vertellen hoe ze werken (Kan altijd nog tijdens overleg)

-   Verder lekker werk Noud! Heb er heel veel zin in en kijk er naar uit om met dit project aan de slag te gaan
