 import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Phone, Mail, Globe } from "lucide-react";

export default function DocumentsOfficiels() { return ( <main className="p-6 max-w-5xl mx-auto space-y-12"> <header className="text-center"> <h1 className="text-4xl font-bold">Documents Officiels 🇫🇷🇧🇪🇨🇦</h1> <p className="mt-2 text-lg text-gray-600"> Simplifiez vos démarches administratives, où que vous soyez. </p> </header>

<section className="grid grid-cols-1 md:grid-cols-2 gap-6">
    <Card>
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold mb-2">🪪 Carte VTC</h2>
        <p>
          Obtenez votre carte professionnelle pour devenir chauffeur VTC en toute légalité.
        </p>
      </CardContent>
    </Card>
    <Card>
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold mb-2">🛂 Titre de Séjour</h2>
        <p>
          Assistance complète pour vos démarches de résidence en France, Belgique ou Canada.
        </p>
      </CardContent>
    </Card>
    <Card>
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold mb-2">🛃 Passeport & Carte d’identité</h2>
        <p>
          Renouvellement ou première demande, nous vous accompagnons pas à pas.
        </p>
      </CardContent>
    </Card>
    <Card>
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold mb-2">🏛️ Autres Documents Officiels</h2>
        <p>
          Actes de naissance, certificats de mariage, permis de conduire, etc.
        </p>
      </CardContent>
    </Card>
  </section>

  <section className="bg-gray-100 p-6 rounded-xl">
    <h2 className="text-2xl font-bold mb-4">🌍 Zones Ciblées</h2>
    <ul className="list-disc list-inside text-gray-700 space-y-1">
      <li>France</li>
      <li>Belgique</li>
      <li>Canada</li>
    </ul>
  </section>

  <section className="p-6 rounded-xl border border-gray-200">
    <h2 className="text-2xl font-bold mb-4">🤝 Pourquoi nous faire confiance ?</h2>
    <ul className="list-disc list-inside space-y-2 text-gray-700">
      <li>✅ Accompagnement personnalisé</li>
      <li>✅ Rapidité et confidentialité</li>
      <li>✅ Réseau de partenaires administratifs</li>
      <li>✅ Disponible 24h/24 – 7j/7</li>
    </ul>
  </section>

  <section className="bg-blue-50 p-6 rounded-xl">
    <h2 className="text-2xl font-bold mb-4">📞 Contact</h2>
    <div className="space-y-2 text-gray-700">
      <p className="flex items-center gap-2"><Mail className="w-5 h-5" /> contact@documents-officiels.com</p>
      <p className="flex items-center gap-2"><Mail className="w-5 h-5" /> titrekondesejours@gmail.com</p>
      <p className="flex items-center gap-2"><Phone className="w-5 h-5" /> +33 6 00 00 00 00</p>
      <p className="flex items-center gap-2"><Globe className="w-5 h-5" /> Telegram: @vtcfree</p>
    </div>
  </section>

  <section className="text-center">
    <Button className="text-lg px-6 py-3">🔐 Accéder à l’Espace Client</Button>
  </section>
</main>

); }


