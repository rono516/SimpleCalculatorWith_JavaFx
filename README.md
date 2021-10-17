# SimpleCalculatorWith_JavaFx
This is a simple Java based Calculator to demonstrate use of JavaFx
Uses lambda (e->) for creating hanlders e.g onclick for button add 
        btAdd.setOnAction(e -> {
            tfResult.setText(Double.parseDouble(tfNumber1.getText())+
                    Double.parseDouble(tfNumber2.getText())+ "");
        });
Also uses Java Fx's Panes, scenes,         
        
