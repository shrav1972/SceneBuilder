# SceneBuilder
FXML CODE
<?xml version="1.0" encoding="UTF-8"?>

<?import javafx.scene.control.*?>
<?import java.lang.*?>
<?import javafx.scene.layout.*?>
<?import javafx.geometry.Insets?>
<?import javafx.scene.layout.GridPane?>
<?import javafx.scene.control.Button?>
<?import javafx.scene.control.Label?>

<GridPane fx:id="GameBoard" alignment="center" hgap="10" prefHeight="242.0" prefWidth="472.0" vgap="10" xmlns="http://javafx.com/javafx/8" xmlns:fx="http://javafx.com/fxml/1" fx:controller="sample.connect4Controller">
    <rowConstraints>
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
        <RowConstraints minHeight="10.0" prefHeight="30.0" />
    </rowConstraints>
    <columnConstraints>
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
        <ColumnConstraints minWidth="10.0" prefWidth="100.0" />
    </columnConstraints>
   <children>
      <Button fx:id="b1" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" />
      <Button fx:id="b2" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" />
      <Button fx:id="b8" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.rowIndex="1" />
      <Button fx:id="b9" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" GridPane.rowIndex="1" />
      <Button fx:id="b15" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.rowIndex="2" />
      <Button fx:id="b3" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" />
      <Button fx:id="b10" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" GridPane.rowIndex="1" />
      <Button fx:id="b22" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.rowIndex="3" />
      <Button fx:id="b29" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.rowIndex="4" />
      <Button fx:id="b37" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" GridPane.rowIndex="5" />
      <Button fx:id="b16" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" GridPane.rowIndex="2" />
      <Button fx:id="b23" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" GridPane.rowIndex="3" />
      <Button fx:id="b30" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="1" GridPane.rowIndex="4" />
      <Button fx:id="b36" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.rowIndex="5" />
      <Button fx:id="b17" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" GridPane.rowIndex="2" />
      <Button fx:id="b4" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" />
      <Button fx:id="b5" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" />
      <Button fx:id="b6" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" />
      <Button fx:id="b7" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" />
      <Button fx:id="b24" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" GridPane.rowIndex="3" />
      <Button fx:id="b31" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" GridPane.rowIndex="4" />
      <Button fx:id="b38" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="2" GridPane.rowIndex="5" />
      <Button fx:id="b11" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" GridPane.rowIndex="1" />
      <Button fx:id="b12" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" GridPane.rowIndex="1" />
      <Button fx:id="b18" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" GridPane.rowIndex="2" />
      <Button fx:id="b25" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" GridPane.rowIndex="3" />
      <Button fx:id="b32" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" GridPane.rowIndex="4" />
      <Button fx:id="b39" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="3" GridPane.rowIndex="5" />
      <Button fx:id="b19" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" GridPane.rowIndex="2" />
      <Button fx:id="b26" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" GridPane.rowIndex="3" />
      <Button fx:id="b33" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" GridPane.rowIndex="4" />
      <Button fx:id="b40" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="4" GridPane.rowIndex="5" />
      <Button fx:id="b13" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" GridPane.rowIndex="1" />
      <Button fx:id="b20" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" GridPane.rowIndex="2" />
      <Button fx:id="b27" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" GridPane.rowIndex="3" />
      <Button fx:id="b34" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" GridPane.rowIndex="4" />
      <Button fx:id="b14" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" GridPane.rowIndex="1" />
      <Button fx:id="b41" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="5" GridPane.rowIndex="5" />
      <Button fx:id="b21" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" GridPane.rowIndex="2" />
      <Button fx:id="b28" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" GridPane.rowIndex="3" />
      <Button fx:id="b35" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" GridPane.rowIndex="4" />
      <Button fx:id="b42" mnemonicParsing="false" prefHeight="31.0" prefWidth="59.0" GridPane.columnIndex="6" GridPane.rowIndex="5" />
   </children>
</GridPane>
