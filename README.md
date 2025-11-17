# DsProject
dataStructures project 
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.hospitalmanagementsystem;

/**
 *
 * @author Momen Ghazzawi
 */
public class Node {
   private int data;
   private Node next;
   private Node previous;
   
  public Node(int data){
      this.data=data;
      this.next=next;
      this.previous=previous;
      
  } 
 //getter and setters
    public int getData() {
        return data;
    }

    public Node getNext() {
        return next;
    }

    public Node getPrevious() {
        return previous;
    }

    public void setData(int data) {
        this.data = data;
    }

    public void setNext(Node next) {
        this.next = next;
    }

    public void setPrevious(Node previous) {
        this.previous = previous;
    }
    //helps for creating objects later 
    @Override
    public String toString(){
        return "Node{"+"data="+data+ '}';
                
        
    }
}

