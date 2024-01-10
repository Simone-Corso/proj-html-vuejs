<template>
    <main>
        <CategoryComponent/>
        <BrandComponent/>
        <LeadingComponent/>
        <GrowthComponent />
        <TeamAvadaComponent />
        <MarketingAdviceComponent />
        <MakeHappenComponent />
    </main>

</template>
<script>
import CategoryComponent from './CategoryComponent.vue';
import BrandComponent from './BrandComponent.vue';
import LeadingComponent from './LeadingComponent.vue';
import GrowthComponent from './GrowthComponent.vue';
import TeamAvadaComponent from './TeamAvadaComponent.vue';
import MarketingAdviceComponent from './MarketingAdviceComponent.vue';
import MakeHappenComponent from './MakeHappenComponent.vue';

export default {
    components: { CategoryComponent,
    BrandComponent,
    LeadingComponent,
    GrowthComponent,
    TeamAvadaComponent, 
    MarketingAdviceComponent,
    MakeHappenComponent, }

}
</script>
<style scoped>


    
       
</style>