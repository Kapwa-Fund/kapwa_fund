<template>
  <div class="min-h-screen bg-white">
    <!-- Article Header -->
    <article class="section-padding">
      <div class="container-max">
        <div class="max-w-4xl mx-auto">
          <!-- Breadcrumb -->
          <nav class="mb-8">
            <ol class="flex items-center space-x-2 text-sm text-gray-500">
              <li><NuxtLink to="/" class="hover:text-blue-600 transition-colors">Home</NuxtLink></li>
              <li>/</li>
              <li><NuxtLink to="/blog" class="hover:text-blue-600 transition-colors">Blog</NuxtLink></li>
              <li>/</li>
              <li class="text-gray-900">Introducing Kapwa Fund</li>
            </ol>
          </nav>

          <!-- Article Meta -->
          <div class="mb-8">
            <div class="flex items-center text-sm text-gray-500 mb-4">
              <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-xs font-semibold mr-4">
                Featured
              </span>
              <time datetime="2025-09-24">September 24, 2025</time>
              <span class="mx-2">•</span>
              <span>8 min read</span>
            </div>
            <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight">
              Introducing Kapwa Fund
            </h1>
            <p class="text-xl text-gray-600 leading-relaxed">
              A platform for citizens to directly support public good projects, without the need for government intermediaries. 
              Building community-driven governance through blockchain and the Filipino concept of Kapwa.
            </p>
          </div>

          <!-- Article Content -->
          <div class="prose prose-lg max-w-none">
            <p class="text-gray-700 leading-relaxed mb-6">
              For centuries, governments have justified their power through the idea of a Social Contract — as Thomas Hobbes framed it, 
              people surrender some freedoms to the state in exchange for order, protection, and public goods. This gave rise to the 
              "Leviathan," a powerful central authority ruling over society.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              The problem is that when too much power is concentrated in a Leviathan, corruption and exploitation follow. Public funds 
              are siphoned off, laws are bent for the powerful, and bureaucracies grow bloated while ordinary citizens are left behind. 
              The very system meant to guarantee fairness becomes a source of inequality and mistrust.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Today, blockchain technology allows us to imagine new ways of working together. Instead of relying on a central authority, 
              we can now build transparent agreements enforced by code — visible to all, tamper-proof, and self-executing.
            </p>

            <h2 class="text-3xl font-bold text-gray-900 mt-12 mb-6">Outgrowing Centralized Power</h2>

            <p class="text-gray-700 leading-relaxed mb-6">
              Blockchain will help us outgrow the Leviathan. Not by tearing it down, but by quietly building alternatives alongside it. 
              Each blockchain-based system we adopt — for payments, community funding, or governance of shared resources — reduces our 
              dependence on the central state. At first, these systems will complement government where trust is weakest. Over time, as 
              people increasingly choose open and self-enforcing agreements, the need for a massive central authority will shrink on its own.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              This is not about seizing power back, but about showing that society can govern itself through networks of trustless systems. 
              The Leviathan will not be toppled — it will simply be outgrown.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              That also means we need to rethink the foundation of governance. The Social Contract once served its purpose, but it may no 
              longer fit a world where decentralized systems can govern fairly and openly.
            </p>

            <h2 class="text-3xl font-bold text-gray-900 mt-12 mb-6">The Kapwa Solution</h2>

            <p class="text-gray-700 leading-relaxed mb-6">
              A core concept in Filipino psychology offers a way forward: <strong>Kapwa</strong>.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Kapwa means seeing ourselves in others — recognizing that our dignity is bound together. While the Social Contract was about 
              individuals giving up rights to a central ruler, Kapwa is about building communities through shared care, reciprocity, and 
              interconnectedness.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Blockchain and Kapwa converge naturally. Blockchain is not about one authority controlling everything, but about open rules 
              enforced by code. Just as Kapwa binds us together in dignity, blockchain binds us in transparent cooperation — without 
              handing power to a Leviathan.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Together, Kapwa and blockchain open the door to a new kind of governance: one rooted not in blind submission, but in shared 
              responsibility. Communities can govern themselves, organize resources without middlemen, fund public goods directly, and build 
              social order founded on trustless systems and human dignity.
            </p>

            <h2 class="text-3xl font-bold text-gray-900 mt-12 mb-6">Introducing Kapwa Fund</h2>

            <p class="text-gray-700 leading-relaxed mb-6">
              That is why we are launching Kapwa Fund — a platform for citizens to directly support public good projects, without the need 
              for government intermediaries. It is a first step in proving that communities, guided by the concept of Kapwa and empowered 
              by blockchain, can manage resources transparently and fairly on their own.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Through Kapwa Fund, we hope to:
            </p>

            <ol class="list-decimal list-inside text-gray-700 leading-relaxed mb-6 space-y-2">
              <li>Show a working alternative to taxes and state-controlled budgets, by letting people directly fund projects they care about.</li>
              <li>Build trust through transparency, since all contributions and spending are recorded on-chain for everyone to see.</li>
              <li>Empower communities to take ownership of public goods, instead of waiting on bureaucrats and politicians.</li>
              <li>Inspire policy change, by demonstrating that voluntary contributions to blockchain-funded projects can be just as impactful — and should be recognized as tax-deductible.</li>
            </ol>

            <p class="text-gray-700 leading-relaxed mb-6">
              Our vision is for Kapwa Fund to spark a gradual cultural shift: from dependence on the central state to self-organized, 
              community-driven governance.
            </p>

            <h2 class="text-3xl font-bold text-gray-900 mt-12 mb-6">How It Works</h2>

            <ul class="list-disc list-inside text-gray-700 leading-relaxed mb-6 space-y-2">
              <li><strong>Project proposals:</strong> Community groups, nonprofits, or individuals can submit public good projects, complete with goals, budgets, and milestones.</li>
              <li><strong>Citizen funding:</strong> Donors contribute directly in Bitcoin Cash or fiat-pegged tokens. Contributions are pooled transparently on-chain, visible to anyone.</li>
              <li><strong>Milestone-based release:</strong> Instead of releasing all funds upfront, smart contracts hold them in escrow and unlock each tranche only when milestones are reached.</li>
              <li><strong>Auditors:</strong> Independent auditors review project progress and submit reports. Auditors must stake funds to ensure honesty.</li>
              <li><strong>Checks and balances:</strong> Donors can review each audit. If an audit is accepted, the auditor is rewarded. If rejected and proven dishonest, the auditor's stake is slashed.</li>
              <li><strong>Permanent record:</strong> All audit documents are digitized, signed, and permanently stored on the blockchain, creating a tamper-proof public archive.</li>
            </ul>

            <p class="text-gray-700 leading-relaxed mb-6">
              This design ensures that projects are accountable to the citizens who fund them, not to politicians or bureaucrats. The long-term 
              vision is to demonstrate that communities can pool and manage resources for public goods more effectively than centralized 
              government planning.
            </p>

            <h2 class="text-3xl font-bold text-gray-900 mt-12 mb-6">The Path Forward</h2>

            <p class="text-gray-700 leading-relaxed mb-6">
              The next step is legislative: pushing for laws that recognize donations made through blockchain platforms like Kapwa Fund as 
              tax-deductible contributions. If citizens and companies can claim these contributions, the incentive to fund community-driven 
              projects will grow — and so will the proof that decentralized governance works.
            </p>

            <p class="text-gray-700 leading-relaxed mb-6">
              Kapwa Fund is just the beginning. It is both a practical tool and a living proof-of-concept that shows another way is possible: 
              communities can pool resources, enforce accountability, and fund public goods without handing power to a Leviathan. If successful, 
              it could mark the start of a quiet but profound shift — from governance built on fear and submission to governance rooted in 
              dignity, reciprocity, and shared responsibility. By combining the wisdom of Kapwa with the trustless transparency of blockchain, 
              we can begin to outgrow the Social Contract and build a new foundation for society — one where citizens truly see themselves in 
              each other and take charge of their shared future.
            </p>
          </div>

          <!-- Article Footer -->
          <div class="mt-12 pt-8 border-t border-gray-200">
            <div class="flex items-center justify-between">
              <NuxtLink 
                to="/blog" 
                class="text-blue-600 hover:text-blue-700 font-semibold transition-colors"
              >
                ← Back to Blog
              </NuxtLink>
              <div class="text-sm text-gray-500">
                Published on September 24, 2025
              </div>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</template>

<script setup>
// SEO and meta tags
useHead({
  title: 'Introducing Kapwa Fund - Blog',
  meta: [
    { name: 'description', content: 'A platform for citizens to directly support public good projects, without the need for government intermediaries. Building community-driven governance through blockchain and the Filipino concept of Kapwa.' }
  ]
})
</script>
