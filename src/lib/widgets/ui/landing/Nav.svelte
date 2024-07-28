
<script>
  const navigation = [
    {
      title: 'Lorem impsum',
      href: '/'
    },
    {
      title: 'Lorem impsum',
      href: '/'
    },
    {
      title: 'Lorem impsum',
      href: '/'
    },
    {
      title: 'Lorem impsum',
      href: '/'
    },
    {
      title: 'Lorem impsum',
      href: '/'
    },
  ];

  let showMenu = true;
</script>

<div class:hidden={showMenu} class="menu">
	<div class="menu-row">
    {#each navigation as nav}
		<a href={nav.href} target="_blank" class="menu-item-mask w-inline-block">
			<div
				class="medium-text"
			>
				<strong>{nav.title}</strong>
			</div>
		</a>
    {/each}
	</div>
	<div class="menu-share-text-mask">
    <div
			class="menu-row"
		>
			<div class="medium-text-copy">
				<strong class="bold-text-2">Share your impressive stats!</strong>
			</div>
			<div class="small-text">
				Tag <span class="text-span-5">
          <a href="/">@agile.fans</a>
        </span> on Instagram.
			</div>
		</div>
	</div>
</div>


<div class="nav h-24" on:click={()=> showMenu = !showMenu}>
	<div class="logo-container">
    <!-- images/NG-Logo.png -->
		<img src="/images/logo.svg" loading="lazy" alt="" class="logo" />
	</div>
	<div class="menu-btn">
    <img
			src="images/closex.svg"
			loading="lazy"
			alt=""
			class="close-x"
		/>
		<img
			src="images/menu-lines.png"
			loading="eager"
			style="display:block;"
			alt=""
			class="image-9"
		/>
	</div>
</div>


<style>
  .logo {
  width: 80%;
  margin-left: 10%;
}

.nav {
  background-color: #ff9461;
  justify-content: space-between;
  display: flex;
}
.logo-container {
  z-index: 2;
  width: 25vw;
  height: 8.33vw;
  border-bottom: 0.5px solid #1a3541;
  border-right: 0.5px solid #1a3541;
  align-items: center;
  display: flex;
  position: relative;
}

.menu-btn {
  z-index: 101;
  width: 8vw;
  height: 8vw;
  cursor: pointer;
  object-fit: cover;
  background-color: rgba(255, 255, 255, 0.25);
  border: 0.5px solid #000;
  border-right-color: #1a3541;
  border-radius: 100px;
  justify-content: center;
  align-self: center;
  align-items: center;
  transition: background-color 50ms;
  display: flex;
  position: relative;
  overflow: visible;
}

.menu {
  z-index: 100;
  height: 100vh;
  background-color: #ff9461;
  flex-direction: column;
  justify-content: center;
  padding-top: 12vh;
  position: absolute;
  top: 0%;
  bottom: 0%;
  left: 0%;
  right: 0%;
  overflow: hidden;
}

.menu-row {
  padding-bottom: 4vh;
  display: inline;
  overflow: visible;
}

.menu-item-mask {
  text-decoration: none;
  display: block;
  overflow: hidden;
}
.menu-share-text-mask {
  margin-top: 15vh;
  margin-bottom: 15vh;
  overflow: hidden;
}

@media screen and (max-width: 479px) {
  .menu-btn {
    width: 16.66vw;
    height: 16.66vw;
    overflow: visible;
  }
  .menu-btn:active {
    background-color: rgba(255, 255, 255, 0.25);
  }
    .menu {
    display: none;
    overflow: hidden;
  }
  .menu-row {
    font-size: 1em;
    line-height: 1.5em;
  }
  .logo-container {
    width: 50vw;
    height: 16.66vw;
  }
}
</style>
