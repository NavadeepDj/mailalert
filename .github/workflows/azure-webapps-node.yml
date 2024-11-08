const nodemailer = require('nodemailer');

// Create a transporter using Gmail credentials
let transporter = nodemailer.createTransport({
  service: 'gmail',
  auth: {
    user: 'sujithgopi740@gmail.com', // replace with your Gmail email
    pass: 'dgbe mtpp oork zlag'      // replace with your Gmail App Password
  }
});

// Set up email data
let mailOptions = {
  from: 'sujithgopi740@gmail.com',                 // sender address
  to: 'tummalamohanaditya119@gmail.com',           // recipient email
  subject: 'SOS from Team SafeTour',               // email subject
  text: `Hello,\n\nThis is an SOS alert from Team SafeTour. Immediate assistance is required.\n\nPlease contact us urgently using the information below:\n\n- Contact: 7989418257\nTeam SafeTour`
};

// Send email
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    return console.log('Error:', error);
  }
  console.log('Email sent:', info.response);
});
