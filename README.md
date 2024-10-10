npx expo-cli init EmiratesHeritageExplorer
cd EmiratesHeritageExplorer
import React from 'react';
import { StyleSheet, Text, View, Button, ScrollView } from 'react-native';

export default function App() {
  return (
    <ScrollView style={styles.container}>
      <Text style={styles.title}>Emirates Heritage Explorer</Text>

      <Text style={styles.sectionTitle}>Featured Heritage Sites</Text>
      <Button title="Al Ain Oasis" onPress={() => alert('Details about Al Ain Oasis')} />
      <Button title="Sheikh Zayed Grand Mosque" onPress={() => alert('Details about Sheikh Zayed Grand Mosque')} />
      <Button title="Bastakiya Quarter" onPress={() => alert('Details about Bastakiya Quarter')} />

      <Text style={styles.sectionTitle}>Traditions</Text>
      <Button title="Falconry" onPress={() => alert('Learn about Falconry')} />
      <Button title="Bedouin Culture" onPress={() => alert('Learn about Bedouin Culture')} />

      <Text style={styles.sectionTitle}>Upcoming Events</Text>
      <Button title="Heritage Festival" onPress={() => alert('Details about Heritage Festival')} />
    </ScrollView>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    padding: 20,
    backgroundColor: '#f0f0f0',
  },
  title: {
    fontSize: 24,
    fontWeight: 'bold',
    marginBottom: 20,
  },
  sectionTitle: {
    fontSize: 20,
    marginVertical: 10,
    fontWeight: 'bold',
  },
});
git init
git add .
git commit -m "Initial commit for Emirates Heritage Explorer"
git remote add origin <your-github-repo-url>
git push -u origin master
