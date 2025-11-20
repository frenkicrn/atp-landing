<script>
    import { MapPin } from 'lucide-svelte';
</script>

<div class="flex flex-col w-full items-center mb-8">
    <div class="flex flex-col w-[90%] items-center rounded-3xl">
        <img src="/arena.svg" alt="Arena" class="w-full -mt-1 -ml-2 -mr-2 rounded-t-3xl">
        <div class="border-l border-r border-b rounded-b-3xl border-white/20 px-3 text-[16px]">
            <h1 class="text-[22px] font-bold pt-4 pb-2">About the ATP Finals</h1>
            <div>Gorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum.</div>
            <div class="flex pt-7 pb-5"><MapPin />Casa di Andrea Salemi, Turin</div>
        </div>
    </div>
    <img src="/racchetta.svg" alt="racchetta" class="absolute -right-28 -bottom-257">
</div>