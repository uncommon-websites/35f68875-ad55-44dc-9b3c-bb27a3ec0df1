<script>
  let activeTab = 'Problem';
  const tabs = ['Problem', 'Investigation', 'Solution', 'Prevention'];
</script>

<section class="py-24 bg-white text-center">
  <div class="max-w-[1200px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-6 tracking-tight text-gray-900">
      Automatic Root Cause<br>Analysis Reports
    </h2>
    
    <!-- Tabs -->
    <div class="flex justify-center mb-8">
      <div class="bg-gray-100 p-1 rounded-lg inline-flex">
        {#each tabs as tab}
          <button 
            class="px-4 py-1.5 text-sm font-medium rounded-md transition-all {activeTab === tab ? 'bg-white text-gray-900 shadow-sm' : 'text-gray-500 hover:text-gray-700'}"
            on:click={() => activeTab = tab}
          >
            {tab}
          </button>
        {/each}
      </div>
    </div>

    <p class="text-lg text-gray-600 mb-16 max-w-2xl mx-auto leading-relaxed">
      Turn team conversations into complete RCA reports automatically.<br>
      Capture the problem, investigation, and solution before knowledge is lost.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden border border-gray-200 text-left h-[700px] flex flex-col">
      <!-- Toolbar -->
      <div class="h-12 border-b border-gray-200 flex items-center justify-between px-4 bg-white">
        <div class="flex items-center gap-4">
           <span class="text-xs font-mono text-gray-500">RCA-2024-03</span>
           <span class="text-gray-300">/</span>
           <span class="text-xs font-bold text-gray-900 flex items-center gap-2">
             <span class="w-2 h-2 rounded-full bg-red-500"></span>
             Line 3 Production Halt
           </span>
        </div>
        
        <div class="flex items-center gap-6">
           <div class="flex items-center gap-4 text-xs font-medium text-gray-500">
              <button class="hover:text-gray-900 flex items-center gap-1"><span>📄</span> Report</button>
              <button class="text-primary-600 flex items-center gap-1 border-b-2 border-primary-600 pb-3 mt-3"><span>💬</span> Discussion <span class="bg-primary-100 text-primary-600 px-1 rounded text-[10px]">8</span></button>
              <button class="hover:text-gray-900 flex items-center gap-1"><span>⏱️</span> Timeline</button>
           </div>
        </div>

        <div class="flex items-center gap-2">
           <button class="text-xs bg-gray-900 text-white rounded px-3 py-1.5 font-medium">Export PDF</button>
        </div>
      </div>

      <div class="flex flex-1 overflow-hidden bg-gray-50 items-center justify-center">
        <div class="text-center p-8">
          <div class="text-gray-400 mb-2">📊</div>
          <p class="text-sm text-gray-500">RCA Report Interface</p>
        </div>
      </div>
    </div>
  </div>
</section>
