<template>
 <div class="header">
                <Navmenu />

                <Container>

                    <Row>
                        <img src={logo} class="logo-header" />
                    </Row>
                    <Row>
                        <h1 class="brand-name">Rachwan</h1>
                    </Row>
                    <Row>
                        <hr class="line-header" />
                    </Row>
                    <Row>
                        <hr class="line-header" />
                    </Row>
                    <Row>
                        <h2 class="tag-line">Reach Your Global</h2>
                    </Row>
                    <Row>
                        <div style={arrow}>
                            <a class="btn-arrow" href="#about">
                                <i class='fas fa-arrow-circle-down'></i>

                            </a>
                        </div>
                    </Row>
                </Container>
            </div >
</template>

<style scoped>
@import "style/App.css";

</style>