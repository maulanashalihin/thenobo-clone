<script>
	import Blog from './lib/Blog.svelte';
	import Hero from './lib/Hero.svelte';
	import LogoAndCategory from './lib/LogoAndCategory.svelte';
  import Header from './lib/Header.svelte';
  import Featured from './lib/Featured.svelte';
import TopDesigners from './lib/TopDesigners.svelte';
import Popular from './lib/Popular.svelte';
import LatestInTrades from './lib/LatestInTrades.svelte';
import TradeStories from './lib/TradeStories.svelte';
import Footer from './lib/Footer.svelte';
</script>
<div class="max-width-6xl">
  <Header></Header>
  <LogoAndCategory></LogoAndCategory>
  <Featured></Featured>
  <Hero></Hero>
  <TopDesigners></TopDesigners>
  <Popular></Popular>
  <LatestInTrades></LatestInTrades>
  <TradeStories></TradeStories>
  <Blog></Blog>
  <Footer></Footer>
</div>