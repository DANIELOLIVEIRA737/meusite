import { useState } from 'react';
import { motion } from 'framer-motion';
import { Button } from '@/components/ui/button';
import { Card, CardContent } from '@/components/ui/card';
import { Input } from '@/components/ui/input';

export default function HomePage() {
  const [email, setEmail] = useState('');

  return (
    <div className="min-h-screen bg-black text-white flex flex-col items-center p-6">
      <motion.h1
        initial={{ opacity: 0, y: -50 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 1 }}
        className="text-5xl font-bold text-blue-500"
      >
        Bem-vindo ao Futuro
      </motion.h1>
      
      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 1.5 }}
        className="mt-4 text-lg"
      >
        Soluções tecnológicas avançadas para sua empresa
      </motion.p>
      
      <Card className="mt-6 w-full max-w-lg bg-gray-900 border border-blue-500">
        <CardContent className="p-6 flex flex-col items-center">
          <h2 className="text-2xl font-semibold">Receba nossas novidades</h2>
          <Input
            className="mt-4 w-full bg-gray-800 text-white border border-gray-600"
            type="email"
            placeholder="Digite seu email"
            value={email}
            onChange={(e) => setEmail(e.target.value)}
          />
          <Button className="mt-4 bg-blue-500 hover:bg-blue-700 text-white">
            Inscrever-se
          </Button>
        </CardContent>
      </Card>
    </div>
  );
}