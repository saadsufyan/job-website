<template>
<div class="mx-auto w-[360px] overflow-y-hidden">
    <div class="relative pt-[75px] h-[640px] bg-gradient-to-r from-[#EBF4FF] to-[#E6FFFA]">
      <div class="fixed w-[360px] top-0 z-10">
        <div class="bg-gradient-to-r from-[#319795] to-[#3182CE] stripTop h-[5px] w-full"></div>
      <div class="h-[62px] bg-white flex justify-end items-center shadow-[0px_3px_6px_#00000029] w-full rounded-b-md">
        <button class="mr-[17px] w-[49px] text-loginColor tracking-[.84px]">Login</button>
      </div>
      </div>
      <div class="content">
        <h1 class="m-[20px] mb-[35px] text-[42px] text-[#2D3748] text-center flex justify-center tracking-[1.26px] leading-[40px]" >Deine Job website</h1>
        <div class="max-w-sm text-center overflow-hidden">
          <img class="max-w-sm " src="../assets/svg/undraw_agreement_aajr.svg">
        </div>
      </div>
      <div class="fixed bottom-[-40px] w-[360px] z-10">
        <div class="h-[128px] bg-white flex justify-center pt-[24px] shadow-[0px_-1px_3px_#00000033;] w-full rounded-t-md p-[20px]">
          <button class="h-[40px] w-[320px] bg-gradient-to-r rounded-md text-white from-[#319795] to-[#3182CE] tracking-[0.84px]">Kostenlos Registrieren</button>
        </div>
      </div>
    </div>
    <div class="second mt-[65px]  overflow-y-hidden">
      <div class="overflow-y-hidden">
        <ul class="flex w-[340px] ml-[20px] text-sm font-medium text-center rounded-lg">
          <li class="w-[160px] flex-none">
              <a href="#" class="w-[160px] h-[40px] flex justify-center  items-center border-tabActiveColor border-[1px] bg-tabActiveColor hover:bg-tabhoverBg text-white rounded-l-lg focus:ring-4 focus:ring-blue-300 active focus:outline-none" aria-current="page">Arbeitnehmer</a>
          </li>
          <li class="w-[160px] h-[40px] flex-none">
              <a href="#" class="w-[160px] h-[40px] flex justify-center items-center border-tabBorder border-[1px] text-loginColor bg-white hover:bg-tabhoverBg focus:ring-4 focus:ring-blue-300 focus:outline-none">Arbeitgeber</a>
          </li>
          <li class="w-[160px] h-[40px] flex-none">
              <a href="#" class="w-[160px] h-[40px] flex justify-center items-center border-tabBorder border-[1px] mr-[20px] text-loginColor hover:bg-tabhoverBg rounded-r-lg bg-white hover:text-gray-700 focus:ring-4 focus:ring-blue-300 focus:outline-none">Temporärbüro</a>
          </li>
      </ul>
    </div>
    <div class="secondHeader mt-[30px] mb-[20px] pl-[50px] pr-[70px]">
      <h4 class="text-secondHeadcolor text-[21px] leading-[25px] text-center">Drei einfache Schritte zu deinem neuen Job</h4>
    </div>
    <div class="section relative pr-[40px] ml-[10px] h-[220px]">
      <div class="img flex justify-end"><img src="../assets/svg/undraw_Profile_data_re_v81r.svg" alt=""></div>
      <div class="flex items-end absolute bottom-0">
        <h1 class="text-secondtextcolor text-[130px] leading-[104px] mr-[21px]">1.</h1>
        <span class="text-secondtextcolor text-[16px] leading-[19px]">Erstellen dein Lebenslauf</span>
      </div>
    </div>
    <div class="section relative pr-[20px] pt-[70px] ml-[35px] h-[370px]">
      <div class="flex items-end">
        <h1 class="text-secondtextcolor text-[130px] leading-[104px] mr-[21px]">2.</h1>
        <span class="text-secondtextcolor text-[16px] leading-[19px]">Erstellen dein Lebenslauf</span>
      </div>
      <div class="img mt-[24px] mr-[37px] flex justify-end"><img src="../assets/svg/undraw_task_31wc.svg" alt=""></div>

    </div>
    <div class="section relative pr-[7px] ml-[54px] mb-[161px] h-[305px]">
      <div class="flex items-end">
        <h1 class="text-secondtextcolor text-[130px] leading-[104px] mr-[21px]">3.</h1>
        <span class="text-secondtextcolor text-[16px] leading-[19px]">Mit nur einem Klick bewerben</span>
      </div>
      <div class="img flex justify-end"><img src="../assets/svg/undraw_personal_file_222m.svg" alt=""></div>

    </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style scoped>

</style>
