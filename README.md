# How-To-Clear-Or-Reset-Input-Field-On-Button-Click-Java-Jframe-Swing-Tutorial-Netbeans
How To Clear/Reset Input Field On Button Click Java Jframe Swing Tutorial - Netbeans
More details - http://mauricemuteti.info/how-to-clear-input-field-on-button-click-java-jframe-swing-tutorial-netbeans/
Video tutorial - https://www.youtube.com/watch?v=m2_8HARrVHY

 Clear Input Fields Function
	
private void clearFields() {
//clears/Resets textfield
    jTextFieldName.setText("");
//clears/Resets button group 1
    buttonGroup1.clearSelection();
//clears/Resets button group 2
    buttonGroup2.clearSelection();
//clears/Resets jcombobox
    jComboBoxSubjects.setSelectedIndex(0);
//clears/Resets image on jlabel
    jLabelImage.setIcon(null);
}

