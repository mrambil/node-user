require('mrambil-phone');

var UserModel;

UserModel = exports = module.exports = {
  attributes: {
    // e.g., "Polly"
    lastname: {
      type: 'string'
    },

    // e.g., 3.26
    firstname: {
      type: 'string',
    },

    // e.g., "cm"
    email: {
      type: 'string',
    },

    comments: {
      type: 'string',
    },

    phone: { model: 'Phone' },
  },

  getFullName: function (){
    return this.firstName + ' ' + this.lastName;
  },
  
  
}
