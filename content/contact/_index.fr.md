---
title: "Contact & Coordonnées"
description: "Contacter le COPAAH"

cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
---


{{< lead >}}
Vous souhaitez nous contacter ? Envoyez-nous un message à l'aide du formulaire ci-joint. Nous vous répondrons dans les plus brefs délais.
{{< /lead >}}


## Formulaire de contact

Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. Faces illo pepulere tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis. 

<!-- @format -->

<!-- FORMS UNSTATIC.COM -->
<!-- 
<form method="post" action="https://forms.un-static.com/forms/5a03fd63611255f2ce4e4ded953595a9390ceff5">
  <div class="form-group row">
    <label for="name" class="col-4 col-form-label">Votre nom</label>
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon"><i class="fa fa-user"></i></div>
        <input name="name" placeholder="Fill in your name" type="text" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="email" class="col-4 col-form-label">Votre e-mail:</label>
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon"><i class="fa fa-envelope"></i></div>
        <input name="email" placeholder="Fill in your e-mail address" type="text" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="message" class="col-4 col-form-label">Message:</label>
    <div class="col-8">
      <textarea name="message" cols="40" rows="8" class="form-control"></textarea>
    </div>
  </div>
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button type="submit" class="btn btn-primary">Send</button>
    </div>
  </div>
  <div class="text-center">
    <p><small>(Powered by <a rel="nofollow" href="https://un-static.com">Un-static Forms</a>)</small></p>
  </div>
</form>
 -->

<!-- RETRAVAILLER EN SHORTCODE POUR CLEANER LE CODE -->
<section class="lg:pb-24">
  <div class="px-4 mx-auto max-w-screen-md">
    <form name="contact" method="post" action="https://forms.un-static.com/forms/5a03fd63611255f2ce4e4ded953595a9390ceff5" class="space-y-8">
        <div class="my-4">
            <label for="name" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50">
                <strong>Votre nom:</strong>
            </label>
            <input type="text" name="name" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="Nom & Prénom" required>
            <label for="email" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50">
                <strong>Votre e-mail: (pour pouvoir vous répondre)</strong>
            </label>
            <input type="email" name="email" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="nom@exemple.com" required>
        </div> 
        <div class="my-4">
            <label for="subject" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50">
                <strong>Objet:</strong>
            </label>
            <input type="text" name="subject" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="Comment pouvons-nous vous aider ?" required>
        </div>
        <div class="my-4 sm:col-span-2">
            <label for="message" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50">
                <strong>Votre message: (mentionner si possible votre fonction)</strong>
            </label>
            <textarea id="message" name="message" rows="6" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-white focus:border-white dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-white dark:focus:border-white" placeholder="Ecrivez votre message ici..."></textarea>
        </div>
        <div class="mt-6 lg:pb-16">
            <button type="submit" class="!rounded-md bg-primary-600 px-4 py-2 !text-neutral !no-underline hover:!bg-primary-500 dark:bg-primary-800 dark:hover:!bg-primary-700">Envoyer</button>
        </div>
    </form>
  </div>
</section>

<!-- MODELE DE FORMS -->
<!-- 
<section class="lg:pb-24">
  <div class="px-4 mx-auto max-w-screen-md">
      <p class="mb-8 font-light text-center text-gray-500 lg:mb-16 dark:text-gray-400 sm:text-xl">Vous souhaitez nous contacter ? Envoyez-nous un message à l'aide du formulaire ci-joint. Nous vous répondrons dans les plus brefs délais.</p>
      <form name="contact" action="mailto:benhaim.david@gmail.com" method="GET" class="space-y-8">
          <div class="my-4">
              <label for="email" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>Votre Email:</strong></label>
              <input type="email" name="email" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="nom@exemple.com" required>
          </div>
          <div class="my-4">
              <label for="subject" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>Objet:</strong></label>
              <input type="text" name="subject" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="Comment pouvons-nous vous aider ?" required>
          </div>
          <div class="my-4 sm:col-span-2">
              <label for="message" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-50"><strong>Votre message:</strong></label>
              <textarea id="message" name="message" rows="6" class="block p-2.5 w-full text-gray-900 bg-gray-50 rounded-lg border border-gray-300 shadow-sm placeholder:text-gray-500 text-md focus:ring-white focus:border-white dark:bg-gray-700 dark:border-gray-600 dark:placeholder:text-gray-300 dark:text-white dark:focus:ring-white dark:focus:border-white" placeholder="Ecrivez votre message ici..."></textarea>
          </div>
          <div class="mt-6 lg:pb-16">
             <button type="submit" class="px-5 py-3 font-bold text-center bg-primary-100 rounded-lg text-md sm:w-fit hover:bg-primary-200 focus:ring-4 focus:outline-none focus:ring-primary-300 dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800">Envoyer</button>
          </div>
      </form>
  </div>
</section>
 -->

## Coordonnées du COPAHH

Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. Faces illo pepulere tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis. 

 - Email:
   * secretariat@copaah.fr (sujets administratifs)
   * tresorerie@copaah.fr (sujets comptables / financiers) 

 - Téléphone de contact: 
   * Dr Françoise ALBERTINI
     Secrétaire du COPAAH
     +33 6 30 90 65 65

## Siège Social

 - Professeur Mélina FATSEAS
   Pôle Addictologie - Bâtiment USN
   Hôpital Haut Lévêque - CHU de Bordeaux
   Avenue de Magellan
   33604 Pessac




### 1 

Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. Faces illo pepulere tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis. 

### 2

Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. Faces illo pepulere tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis. 


---
