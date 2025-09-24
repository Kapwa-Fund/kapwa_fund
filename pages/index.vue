<template>
  <div>
    <!-- Hero Section -->
    <HeroSection />

    <!-- The Problem Section -->
    <section id="problem" class="section-padding bg-white">
      <div class="container-max">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-4xl font-bold text-center mb-12 text-gray-900">
            The Problem with Centralized Power
          </h2>
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <h3 class="text-2xl font-semibold mb-4 text-red-600">Concentrated Power Breeds Corruption</h3>
              <p class="text-gray-600 mb-4">
                For centuries, governments have justified their power through the idea of a Social Contract. 
                People surrender freedoms to the state in exchange for order, protection, and public goods.
              </p>
              <p class="text-gray-600 mb-4">
                But when too much power is concentrated in centralized institutions, corruption and exploitation follow. 
                Public funds are siphoned off, laws are bent for the powerful, and bureaucracies grow bloated 
                while ordinary citizens are left behind.
              </p>
              <p class="text-gray-600">
                The very system meant to guarantee fairness becomes a source of inequality and mistrust.
              </p>
            </div>
            <div class="bg-red-50 p-8 rounded-lg">
              <div class="text-center">
                <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
                  <svg class="w-8 h-8 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-2.5L13.732 4c-.77-.833-1.732-.833-2.5 0L4.268 16.5c-.77.833.192 2.5 1.732 2.5z"></path>
                  </svg>
                </div>
                <h4 class="text-lg font-semibold text-red-800 mb-2">The Centralization Problem</h4>
                <p class="text-red-700">
                  Centralized power leads to corruption, inequality, and loss of citizen agency.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Kapwa Solution Section -->
    <section id="solution" class="section-padding bg-gray-50">
      <div class="container-max">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-4xl font-bold text-center mb-12 text-gray-900">
            The Kapwa Solution
          </h2>
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div class="bg-green-50 p-8 rounded-lg">
              <div class="text-center">
                <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                  <svg class="w-8 h-8 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                  </svg>
                </div>
                <h4 class="text-lg font-semibold text-green-800 mb-2">Kapwa Philosophy</h4>
                <p class="text-green-700">
                  Seeing ourselves in others — recognizing that our dignity is bound together.
                </p>
              </div>
            </div>
            <div>
              <h3 class="text-2xl font-semibold mb-4 text-green-600">Community-Driven Governance</h3>
              <p class="text-gray-600 mb-4">
                A core concept in Filipino psychology offers a way forward: <strong>Kapwa</strong>. 
                While the Social Contract was about individuals giving up rights to a central ruler, 
                Kapwa is about building communities through shared care, reciprocity, and interconnectedness.
              </p>
              <p class="text-gray-600 mb-4">
                Blockchain and Kapwa converge naturally. Blockchain is not about one authority controlling 
                everything, but about open rules enforced by code. Just as Kapwa binds us together in dignity, 
                blockchain binds us in transparent cooperation.
              </p>
              <p class="text-gray-600">
                Together, they open the door to a new kind of governance: one rooted not in blind submission, 
                but in shared responsibility.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- How It Works Section -->
    <section id="how-it-works" class="section-padding bg-white">
      <div class="container-max">
        <div class="max-w-6xl mx-auto">
          <h2 class="text-4xl font-bold text-center mb-12 text-gray-900">
            How Kapwa Fund Works
          </h2>
          <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            <FeatureCard
              step-number="1"
              title="Project Proposals"
              description="Community groups, nonprofits, or individuals submit public good projects with goals, budgets, and milestones."
              card-class="bg-blue-50"
              icon-class="bg-blue-600 text-white"
            />
            
            <FeatureCard
              step-number="2"
              title="Citizen Funding"
              description="Donors contribute directly in Bitcoin Cash or fiat-pegged tokens. All contributions are pooled transparently on-chain."
              card-class="bg-green-50"
              icon-class="bg-green-600 text-white"
            />
            
            <FeatureCard
              step-number="3"
              title="Milestone-Based Release"
              description="Smart contracts hold funds in escrow and unlock each tranche only when milestones are reached."
              card-class="bg-purple-50"
              icon-class="bg-purple-600 text-white"
            />
            
            <FeatureCard
              step-number="4"
              title="Independent Auditors"
              description="Auditors review project progress and submit reports. They must stake funds to ensure honesty."
              card-class="bg-orange-50"
              icon-class="bg-orange-600 text-white"
            />
            
            <FeatureCard
              step-number="5"
              title="Checks and Balances"
              description="Donors review each audit. If accepted, the auditor is rewarded. If rejected and proven dishonest, their stake is slashed."
              card-class="bg-red-50"
              icon-class="bg-red-600 text-white"
            />
            
            <FeatureCard
              step-number="6"
              title="Permanent Record"
              description="All audit documents are digitized, signed, and permanently stored on the blockchain, creating a tamper-proof archive."
              card-class="bg-indigo-50"
              icon-class="bg-indigo-600 text-white"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Vision Section -->
    <section id="vision" class="section-padding bg-gray-50">
      <div class="container-max">
        <div class="max-w-4xl mx-auto text-center">
          <h2 class="text-4xl font-bold mb-8 text-gray-900">
            Our Vision
          </h2>
          <p class="text-xl text-gray-600 mb-12 leading-relaxed">
            Kapwa Fund is both a practical tool and a living proof-of-concept that shows another way is possible: 
            communities can pool resources, enforce accountability, and fund public goods without relying on centralized institutions.
          </p>
          
          <div class="grid md:grid-cols-2 gap-8 mb-12">
            <div class="bg-white p-8 rounded-lg shadow-sm">
              <h3 class="text-2xl font-semibold mb-4 text-blue-600">Immediate Goals</h3>
              <ul class="text-left space-y-3 text-gray-600">
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">•</span>
                  Show alternatives to taxes and state-controlled budgets
                </li>
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">•</span>
                  Build trust through transparent, on-chain contributions
                </li>
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">•</span>
                  Empower communities to take ownership of public goods
                </li>
                <li class="flex items-start">
                  <span class="text-blue-600 mr-2">•</span>
                  Inspire policy change for tax-deductible blockchain donations
                </li>
              </ul>
            </div>
            
            <div class="bg-white p-8 rounded-lg shadow-sm">
              <h3 class="text-2xl font-semibold mb-4 text-green-600">Long-term Vision</h3>
              <p class="text-gray-600 mb-4">
                Spark a gradual cultural shift: from dependence on the central state to self-organized, 
                community-driven governance.
              </p>
              <p class="text-gray-600">
                If successful, Kapwa Fund could mark the start of a quiet but profound shift — from governance 
                built on fear and submission to governance rooted in dignity, reciprocity, and shared responsibility.
              </p>
            </div>
          </div>
          
          <div class="bg-gradient-to-r from-blue-600 to-green-600 text-white p-8 rounded-lg">
            <h3 class="text-2xl font-semibold mb-4">Join the Movement</h3>
            <p class="text-lg mb-6">
              Be part of proving that communities, guided by Kapwa and empowered by blockchain, 
              can manage resources transparently and fairly on their own.
            </p>
            <button class="bg-white text-blue-600 font-semibold py-3 px-8 rounded-lg hover:bg-gray-100 transition-colors">
              Get Started Today
            </button>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Scroll to top button -->
    <ScrollToTop />
  </div>
</template>

<script setup>
// SEO and meta tags
useHead({
  title: 'Kapwa Fund - Building Community Governance',
  meta: [
    { name: 'description', content: 'A platform for citizens to directly support public good projects, without the need for government intermediaries. Building community-driven governance through blockchain and Kapwa.' }
  ]
})
</script>
