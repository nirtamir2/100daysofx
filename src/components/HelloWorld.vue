<template>
  <Card>
    <h1 style="color: red">hi</h1>
    <Button>hi</Button>
    <Button secondary>hi</Button>
  </Card>
</template>

<script>
import Card from '@/components/Card'
import Button from '@/components/Button'

export default {
  name: 'HelloWorld',
  components: { Card, Button }
}
</script>
