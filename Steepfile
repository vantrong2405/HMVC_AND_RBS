target :app do
  signature 'sig'
  library 'stringio'
  library 'rails'
  check 'app'
  
  # Rails specific configurations
  ignore 'app/controllers/application_controller.rb'
  ignore 'app/models/application_record.rb'
  
  # Enable strict type checking
  strict true
end

# Development target for better suggestions
target :dev do
  signature 'sig'
  library 'stringio'
  library 'rails'
  check 'app'
  
  # Less strict for development
  strict false
end
