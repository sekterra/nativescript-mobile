<template>
  <Page class="page">
    <ActionBar class="action-bar" title="Home"/>

    <StackLayout>
      <Button class="btn btn-primary" @tap="$router.push('/counter')">Counter</Button>
      <Button class="btn btn-primary" @tap="$router.push('/hello')">Hello World</Button>
      <Button class="btn btn-primary" @tap="$router.push('/samples/sideDrawer')">sideDrawer</Button>
      <Button class="btn btn-primary" @tap="$router.push('/samples/commonControls')">Common Controls</Button>
    </StackLayout>

  </Page>
</template>
