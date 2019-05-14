template = common layout + style
common layout = page level content + variable part of page (ui:insert name="fragment-name")


Client Page defines the variable part of the layout by using 
 <!-- inclusion of this tag excludes the all content outside of this tag -->
<ui:composition template="./common-layout.xhtml">
  <ui:define name="fragement-name">
  <!-- xhtml fragment supplied by client -->
  </ui:define>
</ui:composition>

**NOTE : <UI:COMPOSITION TAG without 'template' attribute excludes the outside content while being inserted in the resultant template.




