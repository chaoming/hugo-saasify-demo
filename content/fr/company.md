---
title: "À propos de notre entreprise"
layout: "company"
description: "Découvrez notre mission, notre équipe dirigeante et les investisseurs qui soutiennent notre vision"
---

{{< section-container class="bg-gradient-to-b from-blue-50 via-blue-50 to-white pt-20 pb-32" >}}
    <div class="text-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-6">Construire l'avenir du SaaS</h1>
        <p class="text-xl text-gray-600 mb-16">Nous sommes en mission pour révolutionner la façon dont les entreprises fonctionnent à l'ère numérique</p>
        <div class="max-w-3xl mx-auto bg-white rounded-xl shadow-sm p-8">
            <h2 class="text-3xl font-bold mb-4">Notre mission</h2>
            <p class="text-xl text-gray-600">
                Nous nous consacrons à l'autonomisation des entreprises avec des solutions SaaS innovantes qui favorisent la croissance et l'efficacité. Notre plateforme combine une technologie de pointe avec un design intuitif pour résoudre des défis commerciaux complexes.
            </p>
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Équipe dirigeante</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< team-member
                name="Sarah Johnson"
                title="Directrice générale"
                image="/images/company/exec-1.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Michael Chen"
                title="Directeur technique"
                image="/images/company/exec-2.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Emily Rodriguez"
                title="Directrice produit"
                image="/images/company/exec-3.svg"
                linkedin="#"
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Soutenus par des investisseurs de classe mondiale</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 items-center">
            {{< investor-logo name="Sequoia Capital" image="/images/company/investor-1.svg" >}}
            {{< investor-logo name="Andreessen Horowitz" image="/images/company/investor-2.svg" >}}
            {{< investor-logo name="Accel" image="/images/company/investor-3.svg" >}}
            {{< investor-logo name="Benchmark" image="/images/company/investor-4.svg" >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Valeurs de l'entreprise</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< value-card
                title="Innovation d'abord"
                icon="lightbulb"
                description="Nous repoussons constamment les limites et adoptons de nouvelles technologies pour résoudre des défis complexes."
            >}}
            {{< value-card
                title="Réussite client"
                icon="users"
                description="Le succès de nos clients est notre succès. Nous nous engageons à offrir une valeur exceptionnelle."
            >}}
            {{< value-card
                title="Transparence"
                icon="eye"
                description="Nous croyons en une communication ouverte et en l'établissement de la confiance par la transparence."
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
            {{< stat number="2015" label="Fondée" >}}
            {{< stat number="200+" label="Membres d'équipe" >}}
            {{< stat number="10k+" label="Clients" >}}
            {{< stat number="50M+" label="Chiffre d'affaires annuel" >}}
        </div>
    </div>
{{< /section-container >}}
