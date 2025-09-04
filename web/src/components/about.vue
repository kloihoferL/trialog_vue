<script setup>

</script>

<template>
  <section class="relative overflow-hidden">
    <div class="mx-auto max-w-7xl px-6 py-16 lg:py-24">
      <div class="grid items-center gap-12 lg:grid-cols-2">
        <div class="relative">
          <div class="pointer-events-none absolute -left-6 -top-8 hidden h-56 w-56 text-slate-200 dot-grid rounded-3xl lg:block"></div>
          <div class="relative z-10 overflow-hidden rounded-3xl shadow-xl ring-1 ring-black/5">
            <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=1200&auto=format&fit=crop" alt="Mitarbeiterin mit Klemmbrett" class="h-[420px] w-full object-cover" />
          </div>
        </div>

        <!-- Right: content -->
        <div class="relative">
          <div class="mb-5 inline-flex items-center gap-2 rounded-full bg-indigo-50 px-4 py-2 text-sm font-semibold text-[#9a0404]ring-1 ring-indigo-100">
            <span>About Our Company ~</span>
          </div>

          <h1 class="text-4xl font-extrabold tracking-tight text-slate-900 sm:text-5xl">
            Choose <span class="text-[#9a0404]">The Best</span> IT<br class="hidden sm:block" />
            Service Company
          </h1>

          <p class="mt-5 max-w-xl text-slate-600">
            An IT firm or MSP who keeps your IT running smoothly at all times is like a plumber who fixes your pipes; that’s what they are supposed to do. Many IT firms struggle.
          </p>

          <div class="mt-8 border-t border-slate-200 pt-6">
            <div class="grid gap-6 sm:grid-cols-2">
              <div class="flex items-start gap-4">
                <div class="grid h-12 w-12 place-items-center rounded-2xl bg-indigo-50">
                  <svg viewBox="0 0 24 24" fill="none" class="h-6 w-6 text-[#9a0404]">
                    <path d="M9 12l2 2 4-4" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                    <path d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" stroke="currentColor" stroke-width="2"/>
                  </svg>
                </div>
                <div>
                  <p class="text-base font-semibold text-slate-900">Moneyback</p>
                  <p class="text-base font-semibold text-slate-900">Guarantee</p>
                </div>
              </div>

              <div class="flex items-start gap-4">
                <div class="grid h-12 w-12 place-items-center rounded-2xl bg-indigo-50">
                  <svg viewBox="0 0 24 24" fill="none" class="h-6 w-6 text-[#9a0404]">
                    <path d="M4 19h16M8 19V7l8-3v15" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M12 13c2.5 0 2.5-3 5-3" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
                  </svg>
                </div>
                <div>
                  <p class="text-base font-semibold text-slate-900">Technical</p>
                  <p class="text-base font-semibold text-slate-900">Support</p>
                </div>
              </div>
            </div>
          </div>

          <!-- CTA row -->
          <div class="mt-10 flex flex-wrap items-center gap-5">
            <a href="#" class="inline-flex items-center gap-3 rounded-full bg-gradient-to-r bg-[#9a0404] px-6 py-3 text-white shadow-lg transition hover:brightness-110">
              <span class="font-semibold">Erfahre mehr über uns!</span>
              <svg viewBox="0 0 24 24" fill="none" class="h-5 w-5">
                <path d="M5 12h14M13 5l7 7-7 7" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.dot-grid { background-image: radial-gradient(currentColor 1px, transparent 1px); background-size: 12px 12px; }
</style>