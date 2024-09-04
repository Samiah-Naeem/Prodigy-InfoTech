# Prodigy-InfoTech
import matplotlib.pyplot as plt

# Sample data for age distribution
ages = [22, 24, 25, 28, 30, 32, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80]

# Create histogram
plt.figure(figsize=(10, 6))
plt.hist(ages, bins=10, color='purple', edgecolor='black')

# Add title and labels
plt.title('Age Distribution in Population')
plt.xlabel('Age')
plt.ylabel('Frequency')

# Show plot
plt.show()
import matplotlib.pyplot as plt

# Sample data for gender distribution
categories = ['Male', 'Female']
values = [150, 130]

# Create bar chart
plt.figure(figsize=(10, 6))
plt.bar(categories, values, color='lightcoral', edgecolor='black')

# Add title and labels
plt.title('Gender Distribution in Population')
plt.xlabel('Gender')
plt.ylabel('Frequency')

# Show plot
plt.show()
