private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        {
          int parcentile = Integer.parseInt(TF1.getText());
            
            switch (parcentile){
                case 100:
                case 99:
                case 98:
                   TF2.setText("1.00");
                   break;
                case 95:
                case 96:
                case 97:
                    TF2.setText("1.25");
                   break; 
                case 92:
                case 93:
                case 94:
                     TF2.setText("1.50");
                   break;
                case 89:
                case 90:
                case 91:
                    TF2.setText("1.75");
                   break;
                case 85:
                case 86:
                case 87:
                case 88:
                    TF2.setText("2.00");
                   break;
                case 82:
                case 83:
                case 84:
                    TF2.setText("2.25");
                   break;
                case 80:
                case 81:
                    TF2.setText("2.50");
                     break;
                case 77:
                case 78:
                case 79:
                    TF2.setText("2.75");
                     break;
                case 75:
                case 76:
                    TF2.setText("3.00");
                     break;
            }     
        }
    }  
