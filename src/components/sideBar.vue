<template>
  <nav id="sidebar" class="active">
            <div class="sidebar-header">
                <h3>Bootstrap Sidebar</h3>
            </div>

            <ul class="list-unstyled components">
                <p>Dummy Heading</p>

                <router-link to='/' tag="li" active-class="active" exact>
                <a>
                <i class="fa fa-home fa-fw" aria-hidden="true"></i>&nbsp;Home
                </a>
                </router-link>

                <router-link to="/About" tag="li" active-class="active" exact>
                <a>
                  <i class="fa fa-about fa-fw" aria-hidden="true"> </i>
                </a>
                </router-link>
            </ul>

        </nav>
</template>
