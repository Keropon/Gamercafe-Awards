<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";


/*
export default class SplitText extends React.Component {
    render() {
      const condition = this.props.condition;
      const classes = this.props.classes;

      return (
        <span aria-label={this.props.copy} role={this.props.role}>
          {this.props.copy.split("").map(function(char, index){
            let className = null;
            if(condition && classes){
              className = condition === char ? classes[1] : classes[0];   
            }else if(classes){
              className = classes[0];
            }
            return <span
              aria-hidden="true"
              key={index}
              className={className}>
              {char}
            </span>;
          })}
        </span>
      );
    }
  }
  */
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    Vue’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener"
      >official documentation</a
    >
    provides you with all information you need to get started.
  </WelcomeItem>
</template>
