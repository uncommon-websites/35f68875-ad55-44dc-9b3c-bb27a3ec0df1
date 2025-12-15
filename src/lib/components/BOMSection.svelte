<script>
</script>

<section class="bg-[#0B0F19] text-white py-24">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-5xl font-bold mb-6 tracking-tight">
        Searchable Factory Memory
      </h2>
      <p class="text-gray-400 text-lg max-w-2xl mx-auto leading-relaxed">
        Every video, voice note, and conversation becomes part of your factory's permanent memory. Search across years of tribal knowledge in seconds—never lose critical information again.
      </p>
    </div>

    <!-- Search UI Mockup -->
    <div class="bg-white rounded-lg overflow-hidden shadow-2xl mb-20 text-gray-900 mx-auto max-w-[1000px]" generating>
      <!-- Window Header -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center justify-between">
         <div class="flex items-center gap-2">
            <span class="text-xs font-semibold text-gray-700">Factory Knowledge Search</span>
         </div>
         <div class="flex items-center gap-3">
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>🔍</span> Search
            </div>
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>📁</span> Filter
            </div>
            <button class="text-gray-400 hover:text-gray-600">✕</button>
         </div>
      </div>

      <!-- Search Interface -->
      <div class="h-[400px] bg-white relative p-6">
         <!-- Search Bar -->
         <div class="bg-gray-50 border border-gray-200 shadow-sm rounded-lg p-4 flex items-center gap-3 mb-6">
            <span class="text-gray-400 text-xl">🔍</span>
            <input type="text" placeholder="Search factory knowledge..." class="flex-1 bg-transparent text-gray-900 focus:outline-none" value="machine calibration">
            <div class="text-xs text-gray-400">124 results</div>
         </div>
         
         <!-- Search Results Preview -->
         <div class="space-y-3">
            <div class="p-3 bg-gray-50 rounded-lg border border-gray-200 hover:border-primary-400 cursor-pointer">
               <div class="flex items-center gap-2 mb-1">
                  <span class="text-xs font-bold text-gray-900">Machine Calibration SOP</span>
                  <span class="text-[10px] bg-blue-100 text-blue-700 px-2 py-0.5 rounded">Video</span>
               </div>
               <p class="text-xs text-gray-600">Step-by-step calibration procedure for Line 3 equipment...</p>
               <div class="text-[10px] text-gray-400 mt-1">Created 3 days ago by Sarah Chen</div>
            </div>
            <div class="p-3 bg-gray-50 rounded-lg border border-gray-200 hover:border-primary-400 cursor-pointer opacity-70">
               <div class="flex items-center gap-2 mb-1">
                  <span class="text-xs font-bold text-gray-900">Calibration Troubleshooting</span>
                  <span class="text-[10px] bg-green-100 text-green-700 px-2 py-0.5 rounded">Voice</span>
               </div>
               <p class="text-xs text-gray-600">Common issues and solutions when calibration fails...</p>
               <div class="text-[10px] text-gray-400 mt-1">Created 2 weeks ago by Mike Torres</div>
            </div>
            <div class="p-3 bg-gray-50 rounded-lg border border-gray-200 hover:border-primary-400 cursor-pointer opacity-50">
               <div class="flex items-center gap-2 mb-1">
                  <span class="text-xs font-bold text-gray-900">Q3 Calibration RCA</span>
                  <span class="text-[10px] bg-purple-100 text-purple-700 px-2 py-0.5 rounded">RCA</span>
               </div>
               <p class="text-xs text-gray-600">Root cause analysis of calibration drift incident...</p>
               <div class="text-[10px] text-gray-400 mt-1">Created 1 month ago by Eva Debette</div>
            </div>
         </div>
      </div>
    </div>

    <!-- Features Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-x-12 gap-y-16 text-left">
       <!-- Feature 1 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Instant Search</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Find any procedure, solution, or decision in seconds. Search across years of tribal knowledge like searching your email.
          </p>
       </div>

       <!-- Feature 2 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M2 12h20"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Structured Knowledge</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             AI automatically organizes unstructured inputs into clear, searchable documentation with steps, warnings, and key decisions.
          </p>
       </div>

       <!-- Feature 3 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Complete History</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Every capture is timestamped and attributed. Track how processes evolve and who contributed what knowledge.
          </p>
       </div>

       <!-- Feature 4 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Team Knowledge</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Capture knowledge from experienced workers before they retire. Make tribal knowledge accessible to everyone.
          </p>
       </div>

       <!-- Feature 5 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="m19 9-5 5-4-4-3 3"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Continuous Learning</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Your factory memory compounds over time. Each capture makes the system more valuable, creating a competitive advantage.
          </p>
       </div>

       <!-- Feature 6 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Compliance Ready</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Built for regulated manufacturing. Automatic documentation supports audit trails and quality management systems.
          </p>
       </div>
    </div>
  </div>
</section>
