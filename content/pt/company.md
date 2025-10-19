---
title: "Sobre nossa empresa"
layout: "company"
description: "Descubra nossa missão, nossa equipe de liderança e os investidores que apoiam nossa visão"
---

{{< section-container class="bg-gradient-to-b from-blue-50 via-blue-50 to-white pt-20 pb-32" >}}
    <div class="text-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-6">Construindo o futuro do SaaS</h1>
        <p class="text-xl text-gray-600 mb-16">Estamos em uma missão para revolucionar como as empresas operam na era digital</p>
        <div class="max-w-3xl mx-auto bg-white rounded-xl shadow-sm p-8">
            <h2 class="text-3xl font-bold mb-4">Nossa missão</h2>
            <p class="text-xl text-gray-600">
                Nos dedicamos a capacitar empresas com soluções SaaS inovadoras que impulsionam o crescimento e a eficiência. Nossa plataforma combina tecnologia de ponta com design intuitivo para resolver desafios comerciais complexos.
            </p>
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Equipe de liderança</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< team-member
                name="Sarah Johnson"
                title="Diretora Executiva"
                image="/images/company/exec-1.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Michael Chen"
                title="Diretor de Tecnologia"
                image="/images/company/exec-2.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Emily Rodriguez"
                title="Diretora de Produto"
                image="/images/company/exec-3.svg"
                linkedin="#"
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Apoiados por investidores de classe mundial</h2>
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
        <h2 class="text-3xl font-bold text-center mb-12">Valores da empresa</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< value-card
                title="Inovação primeiro"
                icon="lightbulb"
                description="Constantemente empurramos limites e adotamos novas tecnologias para resolver desafios complexos."
            >}}
            {{< value-card
                title="Sucesso do cliente"
                icon="users"
                description="O sucesso de nossos clientes é nosso sucesso. Estamos comprometidos em entregar valor excepcional."
            >}}
            {{< value-card
                title="Transparência"
                icon="eye"
                description="Acreditamos em comunicação aberta e construir confiança através da transparência."
            >}}
        </div>
    </div>
{{< /section-container >}}
