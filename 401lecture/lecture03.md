# basic express server  

If your endpoint function requires a dependency you may need to curry functions.  

## express server  

Adding CRUD and a data layer to our server.  
Sequelize converts our javascript values into sql values to be stored in our data layer.  
A model is a table in the sql database.  
records are rows.  
Object relational mapper is taking data from one language and putting it into another.  
Install sequilize, pg, and sqlite.  
Models folder is for all sequlize functions for the server to use.  
index.js intializes all functions from our models folder.  

const { sequlize, DataTypes } = require('sequlize');  
const DATABASE_URL = process.env.DATABASE_URL || 'sqlite:memory:';  
const messagesSchema = require('./messages.js')

let seqeulize = new Sewuelize(DATABASE_URL);  

let MessagesModel = messageSchema(squelize, DataTypes);  

module.exports = {
    Messages: MessagesModel,
    db: sequelize,
};

// in messages.js define the model  

const messagesSChema = (sequlize, DataTypes) => 
sequilize.define(
    'Messages',{
    text: {
        type: DataTypes.STRING,
        allowNull: false,
    },
    }
)  

A singleton refers to only a single instance. Don't use it more than once.  

// test models  

const {Messages, db} = require('../lib/models/index.js')  

// Jest specific. Used in most testers
beforeAll(async () => {
    await db.sync();
});  

describe('Testing data models', () => {
    test ('Should create a single messge', async () => {
        let message = await Messages.creat({
            text: 'My first message',
        })
       expect(message.id).toBeTruthy();
       expect(message.text).toEqual('My first message)
    })
    test ('should read from our message;, async() => {
        let messages = await Messages.findAll();
        expect(messages.length).toBeTruthy();

    })
    test('Should be a single message', async() => {
        await Messages.Update({text:"Updated Text!"} , {where: {id: 1}};
        let message = await Messages.findOne ({ where: {id:1}})
        expect(message.text).toEqual('Updated Text!')
        })
    })
    test ('Should delete message', async () => {
        await Messages.destroy{{where: {id:1}}};
        let message = await MEssages.findOne({ where: {id: 1}})
        expect(messsage).not.toBeTruthy();
    })
})

// Always be sure to add test scripts  
// test read capability  

// server.js  

'use strict';  
const express = require('express');
const app = express();  
app.post('./message', (request,response))  

sync database with db.sync() before starting the server.  
