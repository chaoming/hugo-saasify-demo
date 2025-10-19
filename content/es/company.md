---
title: "Acerca de nuestra empresa"
layout: "company"
description: "Descubre nuestra misión, nuestro equipo de liderazgo y los inversores que apoyan nuestra visión"
---

{{< section-container class="bg-gradient-to-b from-blue-50 via-blue-50 to-white pt-20 pb-32" >}}
    <div class="text-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-6">Construyendo el futuro de SaaS</h1>
        <p class="text-xl text-gray-600 mb-16">Estamos en una misión para revolucionar cómo las empresas operan en la era digital</p>
        <div class="max-w-3xl mx-auto bg-white rounded-xl shadow-sm p-8">
            <h2 class="text-3xl font-bold mb-4">Nuestra misión</h2>
            <p class="text-xl text-gray-600">
                Nos dedicamos a empoderar a las empresas con soluciones SaaS innovadoras que impulsan el crecimiento y la eficiencia. Nuestra plataforma combina tecnología de vanguardia con diseño intuitivo para resolver desafíos comerciales complejos.
            </p>
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20 bg-gray-50" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Equipo de liderazgo</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< team-member
                name="Sarah Johnson"
                title="Directora Ejecutiva"
                image="/images/company/exec-1.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Michael Chen"
                title="Director de Tecnología"
                image="/images/company/exec-2.svg"
                linkedin="#"
            >}}
            {{< team-member
                name="Emily Rodriguez"
                title="Directora de Producto"
                image="/images/company/exec-3.svg"
                linkedin="#"
            >}}
        </div>
    </div>
{{< /section-container >}}

{{< section-container class="py-20" >}}
    <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12">Respaldados por inversores de clase mundial</h2>
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
        <h2 class="text-3xl font-bold text-center mb-12">Valores de la empresa</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            {{< value-card
                title="Innovación primero"
                icon="lightbulb"
                description="Constantemente empujamos límites y adoptamos nuevas tecnologías para resolver desafíos complejos."
            >}}
            {{< value-card
                title="Éxito del cliente"
                icon="users"
                description="El éxito de nuestros clientes es nuestro éxito. Estamos comprometidos a entregar valor excepcional."
            >}}
            {{< value-card
                title="Transparencia"
                icon="eye"
                description="Creemos en la comunicación abierta y en construir confianza a través de la transparencia."
            >}}
        </div>
    </div>
{{< /section-container >}}
